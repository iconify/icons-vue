<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="is-su-b3s"/><path class="sjnnzzbvw"/><path class="k35ip_tgj"/><path class="v0kumqbum"/><path class="jf6mfo6-x"/><path class="a5_bcnr6g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:truck-broken" /></template>
<style>
.a5_bcnr6g {
  d: path("M19.75 17.875C19.75 19.1176 18.7426 20.125 17.5 20.125C16.2574 20.125 15.25 19.1176 15.25 17.875C15.25 16.6324 16.2574 15.625 17.5 15.625C18.7426 15.625 19.75 16.6324 19.75 17.875Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.is-su-b3s {
  d: path("M4.75 17.875H4C3.0572 17.875 2.5858 17.875 2.2929 17.5821C2 17.2892 2 16.8178 2 15.875V7.075C2 5.5665 2 4.8123 2.4686 4.3436C2.9373 3.875 3.6915 3.875 5.2 3.875H6.3");
}

.jf6mfo6-x {
  d: path("M9.25 17.875C9.25 19.1176 8.2426 20.125 7 20.125C5.7574 20.125 4.75 19.1176 4.75 17.875C4.75 16.6324 5.7574 15.625 7 15.625C8.2426 15.625 9.25 16.6324 9.25 17.875Z");
}

.k35ip_tgj {
  d: path("M14 8.375H17C17.7542 8.375 18.1314 8.375 18.5069 8.562C18.8825 8.7489 19.1099 9.0498 19.5645 9.6516L21.0355 11.5984L21.0363 11.5994C21.4904 12.2005 21.7176 12.5013 21.8587 12.9224C22 13.3436 22 13.7208 22 14.475V15.875C22 16.8178 22 17.2892 21.7071 17.5821C21.4142 17.875 20.9428 17.875 20 17.875H19.75");
}

.sjnnzzbvw {
  d: path("M9.69922 3.875H10.7992C12.3077 3.875 13.0619 3.875 13.5306 4.3436C13.9992 4.8123 13.9992 5.5665 13.9992 7.075V17.875");
}

.v0kumqbum {
  d: path("M9.25 17.875H15.25");
}

</style>
