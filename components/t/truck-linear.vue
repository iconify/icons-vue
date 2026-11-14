<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b3soe7g-t"/><path class="k35ip_tgj"/><path class="v0kumqbum"/><path class="jf6mfo6-x"/><path class="a5_bcnr6g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:truck-linear" /></template>
<style>
.a5_bcnr6g {
  d: path("M19.75 17.875C19.75 19.1176 18.7426 20.125 17.5 20.125C16.2574 20.125 15.25 19.1176 15.25 17.875C15.25 16.6324 16.2574 15.625 17.5 15.625C18.7426 15.625 19.75 16.6324 19.75 17.875Z");
}

.b3soe7g-t {
  d: path("M4.75 17.875H4C3.0572 17.875 2.5858 17.875 2.2929 17.5821C2 17.2892 2 16.8178 2 15.875V7.075C2 5.5665 2 4.8123 2.4686 4.3436C2.9373 3.875 3.6915 3.875 5.2 3.875H10.8C12.3085 3.875 13.0627 3.875 13.5314 4.3436C14 4.8123 14 5.5665 14 7.075V17.875");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jf6mfo6-x {
  d: path("M9.25 17.875C9.25 19.1176 8.2426 20.125 7 20.125C5.7574 20.125 4.75 19.1176 4.75 17.875C4.75 16.6324 5.7574 15.625 7 15.625C8.2426 15.625 9.25 16.6324 9.25 17.875Z");
}

.k35ip_tgj {
  d: path("M14 8.375H17C17.7542 8.375 18.1314 8.375 18.5069 8.562C18.8825 8.7489 19.1099 9.0498 19.5645 9.6516L21.0355 11.5984L21.0363 11.5994C21.4904 12.2005 21.7176 12.5013 21.8587 12.9224C22 13.3436 22 13.7208 22 14.475V15.875C22 16.8178 22 17.2892 21.7071 17.5821C21.4142 17.875 20.9428 17.875 20 17.875H19.75");
}

.v0kumqbum {
  d: path("M9.25 17.875H15.25");
}

</style>
