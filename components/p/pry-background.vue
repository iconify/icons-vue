<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="wute-9bsg"/><path class="rszcu_b3i"/><path class="j61demleo"/><path class="b2s0f6kyr"/><path class="faqa8-7bv"/><path class="t1oru6iha"/><path class="f691vob5a"/><path class="mtyw5jbrt"/><path class="xbcxs1njk"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pry-background" /></template>
<style>
.b2s0f6kyr {
  fill: var(--svg-color--000, #000);
  d: path("M13.333 6.6q.226.054.444.13v5.048h3.832q.01.223.004.445h-4.28z");
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.f691vob5a {
  fill: var(--svg-color--000, #000);
  d: path("M9.333 7.112q.22-.116.454-.218v4.44h-3.36c.022-.151.044-.298.075-.444h2.831z");
}

.faqa8-7bv {
  fill: var(--svg-color--000, #000);
  d: path("M12.445 6.444c.151.014.298.045.445.067v6.156h4.693a4 4 0 0 1-.067.444h-5.07zm-1.333.067c.146-.022.293-.053.444-.067v6.667h-5.07a4 4 0 0 1-.068-.444h4.694z");
}

.ft5dv1b6b {
  fill: none;
}

.j61demleo {
  fill: var(--svg-color--000, #000);
  d: path("M14.214 6.894q.232.101.453.222v3.774h2.831q.045.218.076.444h-3.36z");
}

.mtyw5jbrt {
  fill: var(--svg-color--000, #000);
  d: path("M8.445 7.706q.212-.172.444-.324v3.062H6.62c.044-.142.088-.284.141-.422h1.685z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rszcu_b3i {
  fill: var(--svg-color--000, #000);
  d: path("M15.112 7.378c.155.107.302.214.444.33V10l1.676.004q.086.213.15.44h-2.27z");
}

.t1oru6iha {
  fill: var(--svg-color--000, #000);
  d: path("M10.223 6.73c.146-.05.293-.09.444-.13v5.623h-4.28a6 6 0 0 1 0-.445h3.836z");
}

.wute-9bsg {
  fill: var(--svg-color--000, #000);
  d: path("M4 17.111h16v.445H4zm0-.889h16v.445H4zm13.031-6.666a5 5 0 0 0-.244-.445h-.343v-.489a5 5 0 0 0-.444-.51v1.444z");
}

.xbcxs1njk {
  fill: var(--svg-color--000, #000);
  d: path("M7.556 8.622c.138-.177.284-.35.444-.51v1.444H6.97q.112-.228.244-.445h.342zM6.734 14a5 5 0 0 1-.147-.444h10.827a5 5 0 0 1-.147.444zm.422.89a4 4 0 0 1-.236-.445h10.16a5 5 0 0 1-.235.444zm.644.888a6 6 0 0 1-.355-.444h9.11a6 6 0 0 1-.355.444z");
}

</style>
