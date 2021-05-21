<template>
  <main>
    <AyudarSlider />
    <section class="bg-white only-links-to">
      <div class="container">
        <div
          class="d-flex flex-wrap for-mg justify-content-center ff-nunito justify-content-start-767"
        >
          <div
            @click="primeraEdicion"
            class="linkse d-flex justify-content-center align-items-center text-center"
          >
            Primera Edición
          </div>
          <div
            @click="segundaEdicion"
            class="linkse d-flex justify-content-center align-items-center text-center"
          >
            Segunda Edición
          </div>
          <div
            @click="terceraEdicion"
            class="linkse d-flex justify-content-center align-items-center text-center"
          >
            Tercera Edición
          </div>
        </div>
      </div>
    </section>
    <section v-if="show2"
      class="ig-tx-zing-zag desarrolla bg-white des-filarmonic-main desarroll-te-empre"
    >
      <div class="container">
        <div class="sm-siz-container margin-0-auto">
          <div class="text-center">
            <h2 class="ff-sans-b d-none-991 mb-4" data-wow-duration="2s">
            Segunda Edición
          </h2>
          </div>
          <div class="d-flex multiple-reapt align-items-start flex-wrap-991">
            <h2 class="ff-sans-b ss d-block-991 d-none-n">
              Así conectamos <br />
              el talento con <br />
              el cambio
            </h2>
            <h4 class="extr-tx ff-nunito d-block-991 d-none-n text-uppercase">
              Emprendedores que <br />
              sueñan, <br />
              viven <br />
              y creen.
            </h4>
            <div class="txt-points position-relative order-2-991">
              <h2 class="ff-sans-b d-none-991">
                Así conectamos <br />
                el talento con <br />
                el cambio
              </h2>
              <h4 class="extr-tx ff-nunito d-none-991 text-uppercase">
                Emprendedores que <br />
                sueñan, <br />
                viven <br />
                y creen.
              </h4>
              <div class="pra-p for-bgcol">
                <p>
                  En la Fundación Bolivar Davivienda trabajamos para entender,
                  ayudar e inspirar a quienes lo necesitan para trascender y
                  desarrollar su talento. Conocer de la experiencia de otros
                  puede inspirarnos para encontrar el camino del éxito. Una guía
                  oportuna puede hacer la diferencia.
                </p>
              </div>
            </div>
            <div class="img-points order-1-991">
              <img
                src="/images/desarrollamostalento_bloque_1b_860044a.jpg"
                alt=""
                class="object-fit-cover"
              />
            </div>
          </div>
        </div>
        <div class="container mt-5">
        <div class="text-center">
          <h3
          class="ff-sans-b mb-5 text-center"
          style="color: #ff671b; padding-left: 20px; padding-right: 20px"
        >
          Conozca los momentos significativos de emprendimientos que soñaron,
          vivieron y creyeron en su proyecto.
        </h3>
        </div>
        <b-row>
          <b-col md="6">
            <iframe
              class="yt-vids-size"
              src="https://www.youtube.com/embed/D5T3y4ljlTU"
              title="YouTube video player"
              frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen
            ></iframe>
          </b-col>
          <b-col md="6">
            <iframe
              class="yt-vids-size"
              src="https://www.youtube.com/embed/D5T3y4ljlTU"
              title="YouTube video player"
              frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen
            ></iframe>
          </b-col>
        </b-row>
        <b-row>
          <b-col md="6">
            <iframe
              class="yt-vids-size"
              src="https://www.youtube.com/embed/D5T3y4ljlTU"
              title="YouTube video player"
              frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen
            ></iframe>
          </b-col>
          <b-col md="6">
            <iframe
              class="yt-vids-size"
              src="https://www.youtube.com/embed/D5T3y4ljlTU"
              title="YouTube video player"
              frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen
            ></iframe>
          </b-col>
        </b-row>
        <b-row>
          <b-col md="6">
            <iframe
              class="yt-vids-size"
              src="https://www.youtube.com/embed/D5T3y4ljlTU"
              title="YouTube video player"
              frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen
            ></iframe>
          </b-col>
          <b-col md="6">
            <iframe
              class="yt-vids-size"
              src="https://www.youtube.com/embed/D5T3y4ljlTU"
              title="YouTube video player"
              frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen
            ></iframe>
          </b-col>
        </b-row>
      </div>
      </div>
    </section>
    <section v-if="show1"
      class="ig-tx-zing-zag desarrolla bg-white des-filarmonic-main desarroll-te-empre"
    >
      <div class="container">
        <div class="sm-siz-container margin-0-auto">
          <div class="text-center">
            <h2 class="ff-sans-b d-none-991 mb-4" data-wow-duration="2s">
            Primera Edición
          </h2>
          </div>
          <div class="d-flex multiple-reapt align-items-start flex-wrap-991">
            <h2 class="ff-sans-b ss d-block-991 d-none-n">
              Así conectamos <br />
              el talento con <br />
              el cambio
            </h2>
            <h4 class="extr-tx ff-nunito d-block-991 d-none-n text-uppercase">
              Emprendedores que <br />
              sueñan, <br />
              viven <br />
              y creen.
            </h4>
            <div class="txt-points position-relative order-2-991">
              <h2 class="ff-sans-b d-none-991">
                Así conectamos <br />
                el talento con <br />
                el cambio
              </h2>
              <h4 class="extr-tx ff-nunito d-none-991 text-uppercase">
                Emprendedores que <br />
                sueñan, <br />
                viven <br />
                y creen.
              </h4>
              <div class="pra-p for-bgcol">
                <p>
                  En la Fundación Bolivar Davivienda trabajamos para entender,
                  ayudar e inspirar a quienes lo necesitan para trascender y
                  desarrollar su talento. Conocer de la experiencia de otros
                  puede inspirarnos para encontrar el camino del éxito. Una guía
                  oportuna puede hacer la diferencia.
                </p>
              </div>
            </div>
            <div class="img-points order-1-991">
              <img
                src="/images/desarrollamostalento_bloque_1b_860044a.jpg"
                alt=""
                class="object-fit-cover"
              />
            </div>
          </div>
        </div>
        <div class="container mt-5">
        <div class="text-center">
          <h3
          class="ff-sans-b mb-5 text-center"
          style="color: #ff671b; padding-left: 20px; padding-right: 20px"
        >
          Conozca los momentos significativos de emprendimientos que soñaron,
          vivieron y creyeron en su proyecto.
        </h3>
        </div>
        <b-row>
          <b-col md="6">
            <iframe
              class="yt-vids-size"
              src="https://www.youtube.com/embed/D5T3y4ljlTU"
              title="YouTube video player"
              frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen
            ></iframe>
          </b-col>
          <b-col md="6">
            <iframe
              class="yt-vids-size"
              src="https://www.youtube.com/embed/D5T3y4ljlTU"
              title="YouTube video player"
              frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen
            ></iframe>
          </b-col>
        </b-row>
        <b-row>
          <b-col md="6">
            <iframe
              class="yt-vids-size"
              src="https://www.youtube.com/embed/D5T3y4ljlTU"
              title="YouTube video player"
              frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen
            ></iframe>
          </b-col>
          <b-col md="6">
            <iframe
              class="yt-vids-size"
              src="https://www.youtube.com/embed/D5T3y4ljlTU"
              title="YouTube video player"
              frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen
            ></iframe>
          </b-col>
        </b-row>
      </div>
      </div>
    </section>
    <section
      v-if="show3"
      class="bg-white what-we-do position-relative filamonica-pg-main"
    >
      <HomeDots></HomeDots>
      <div class="container">
        <div class="d-flex align-items-start flex-wrap-991">
          <div
            class="txt-bx-wht position-relative order-2-991 wow bounceInLeft"
            data-wow-duration="2s"
          >
            <h2 class="ff-sans-b">Tercera Edición</h2>
            <div class="pra-p ff-nunito">
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
                Suscipit maiores praesentium vero iste earum perferendis
                inventore illo saepe perspiciatis laboriosam eligendi dolore,
                facere provident, rerum quisquam iusto quidem minima officiis
                sapiente nisi, soluta in! Dolor doloribus vel sit mollitia
                perspiciatis velit, consequuntur facilis eligendi minima,
                voluptas excepturi maiores laudantium nihil at nostrum adipisci
                tempore, earum cum aspernatur unde expedita in!
              </p>
            </div>
          </div>
          <div
            class="img-rrt-pr order-1-991 wow bounceInRight"
            data-wow-duration="2s"
          >
            <img
              src="/images/rectangle_l.jpg"
              alt=""
              class="object-fit-cover"
            />
          </div>
        </div>
      </div>
    </section>
  </main>
</template>

<script>
import AyudarSlider from '@/components/ayudarinspira/Slider'
import HomeDots from '@/components/home/dots'
import HomeDotsbottoms from '@/components/home/dotsbottoms'

export default {
  data: () => {
    return {
      show1: false,
      show2: true,
      show3: false,
    }
  },
  methods: {
    primeraEdicion() {
      this.show1 = true
      this.show2 = false
      this.show3 = false
    },
    segundaEdicion() {
      this.show1 = false
      this.show2 = true
      this.show3 = false
    },
    terceraEdicion() {
      this.show1 = false
      this.show2 = false
      this.show3 = true
    },
  },
  components: {
    AyudarSlider,
    HomeDots,
    HomeDotsbottoms,
  },
}
</script>
