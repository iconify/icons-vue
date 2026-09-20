<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfybr4bju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:shopping-cart-outline-sharp" /></template>
<style>
.gfybr4bju {
  fill: currentColor;
  d: path("M5.588 21.413Q5 20.825 5 20t.588-1.412T7 18t1.413.588T9 20t-.587 1.413T7 22t-1.412-.587m10 0Q15 20.825 15 20t.588-1.412T17 18t1.413.588T19 20t-.587 1.413T17 22t-1.412-.587M6.15 6l2.4 5h7l2.75-5zM5.2 4h16.5l-4.975 9H8.1L7 15h12v2H3.625L6.6 11.6L3 4H1V2h3.25zm3.35 7h7z");
}

</style>
