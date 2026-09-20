<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7an0_cgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:playing-cards" /></template>
<style>
.l7an0_cgm {
  fill: currentColor;
  d: path("m14.93 14.03l.862-3.13l-2.684-1.854l-.862 3.131zM4.617 19.288l-.422-.189q-.794-.344-1.069-1.141q-.275-.798.075-1.553l1.416-3.035zM9 20.769q-.825 0-1.412-.59Q7 19.589 7 18.764v-4.725l2.214 6.08q.074.195.144.347q.069.153.194.303zm4.362-.971q-.64.237-1.243-.036t-.838-.914L7.22 7.7q-.236-.64.046-1.24t.923-.835l6.41-2.346q.64-.237 1.24.046t.835.923l4.066 11.148q.236.64-.037 1.24q-.273.599-.914.835z");
}

</style>
