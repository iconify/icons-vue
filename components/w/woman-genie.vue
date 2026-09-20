<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<ellipse class="jg-ua2bvf"/><ellipse class="w-xvs0bvs"/><ellipse class="r022m4brp"/><path class="zpxkx1d8h"/><path class="sl4d02_3j"/><path class="vffvevb6e"/><path class="emqmq6mkh"/><path class="o1010789m"/><path class="qt4_jqbff"/><path class="g3hbq3bow"/><path class="e0u9w2b0e"/><ellipse transform="rotate(-21.844 10.413 16.5)" class="hrfozybwq"/><ellipse transform="rotate(-68.155 25.587 16.5)" class="d7fhvza1z"/><path class="h5t3jub1q"/><path class="eunsirqxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:woman-genie" /></template>
<style>
.d7fhvza1z {
  cx: 25.587px;
  cy: 16.5px;
  fill: var(--svg-color--88c9f9, #88c9f9);
  rx: 2.5px;
  ry: 1.5px;
}

.e0u9w2b0e {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M18.052 3C26.107 3 29 9.197 29 15.123S26.107 23 26.107 23s1-1.951 0-3.902s-1-5.854-1-5.854s-2.879-.286-5-.976c-3-.976-4-1.951-4-1.951s-3 2.927-5 2.927c0 0 0 1.951-1 4.878c-.632 1.851 0 4.878 0 4.878s-3-2.927-3-8.78S9.996 3 18.052 3");
}

.emqmq6mkh {
  fill: var(--svg-color--88c9f9, #88c9f9);
  d: path("M10.734 14.627c0-5.834 3.229-10.563 7.211-10.563c3.981 0 7.209 4.73 7.209 10.563s-3.228 10.285-7.209 10.285c-3.983 0-7.211-4.452-7.211-10.285");
}

.eunsirqxt {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M18 29c3 0 4-3 4-3h1s0 5-5 5s-5-5-5-5h1s1 3 4 3");
}

.g3hbq3bow {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M18.836 19.409h-1.69a.424.424 0 0 1-.423-.423v-.153c0-.233.189-.424.423-.424h1.69c.233 0 .424.19.424.424v.153a.424.424 0 0 1-.424.423");
}

.h5t3jub1q {
  fill: var(--svg-color--a0041e, #a0041e);
  d: path("M9 36s-1-3 1-4c2.828-1.414 7 3 8 3s5.172-4.414 8-3c2 1 1 4 1 4z");
}

.hrfozybwq {
  cx: 10.413px;
  cy: 16.5px;
  fill: var(--svg-color--88c9f9, #88c9f9);
  rx: 1.5px;
  ry: 2.5px;
}

.jg-ua2bvf {
  cx: 18px;
  cy: 3.5px;
  fill: var(--svg-color--292f33, #292f33);
  rx: 4px;
  ry: 3.5px;
}

.o1010789m {
  fill: var(--svg-color--df1f32, #df1f32);
  d: path("M17.945 22.452c-1.606 0-2.447-.794-2.537-.885a.685.685 0 0 1 .961-.974c.035.032.551.491 1.576.491c1.038 0 1.555-.473 1.576-.492a.69.69 0 0 1 .963.02c.26.269.26.691-.004.955c-.089.091-.929.885-2.535.885");
}

.qt4_jqbff {
  fill: var(--svg-color--662113, #662113);
  d: path("M14.608 16.796a.85.85 0 0 1-.846-.847v-.845c0-.465.381-.846.846-.846a.85.85 0 0 1 .847.846v.845a.85.85 0 0 1-.847.847m6.765 0a.85.85 0 0 1-.846-.847v-.845c0-.465.381-.846.846-.846s.846.381.846.846v.845a.85.85 0 0 1-.846.847");
}

.r022m4brp {
  cx: 18px;
  cy: 4px;
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  rx: 3px;
  ry: 2px;
}

.sl4d02_3j {
  fill: var(--svg-color--88c9f9, #88c9f9);
  d: path("M14.5 26.518c1.466 1.065 2.792.98 3.5.98s2.194.085 3.488-.949l.012-4.14h-7z");
}

.vffvevb6e {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M14.483 24.438c.973.938 2.674 1.118 3.508 1.118c.823 0 2.537-.181 3.51-1.118v-3.286h-7.017z");
}

.w-xvs0bvs {
  cx: 18px;
  cy: 16px;
  fill: var(--svg-color--292f33, #292f33);
  rx: 12px;
  ry: 10px;
}

.zpxkx1d8h {
  fill: var(--svg-color--88c9f9, #88c9f9);
  d: path("M31 36v-4.5c0-3.314-3.56-5.5-6.875-5.5h-12C8.812 26 5 28.186 5 31.5V36z");
}

</style>
