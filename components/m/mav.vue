<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGb25sIdga)" class="umeew3kms"/><path fill="url(#SVGqh8dHcFB)" clip-rule="evenodd" class="qplfb_y-j"/><defs><linearGradient id="SVGb25sIdga" x1="8.368" x2="12.519" y1="8.726" y2="16.243" gradientUnits="userSpaceOnUse"><stop offset=".03" class="hfn4j9bst"/><stop offset=".69" class="km_rl6s3m"/></linearGradient><linearGradient id="SVGqh8dHcFB" x1="6.388" x2="18.114" y1="5.321" y2="18.898" gradientUnits="userSpaceOnUse"><stop offset=".03" class="hfn4j9bst"/><stop offset=".69" class="km_rl6s3m"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mav" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hfn4j9bst {
  stop-color: var(--svg-color--d3606c, #d3606c);
}

.km_rl6s3m {
  stop-color: var(--svg-color--5b7cfd, #5b7cfd);
}

.qplfb_y-j {
  fill-rule: evenodd;
  d: path("M12 21a9 9 0 1 0 0-18a9 9 0 0 0 0 18m0-.53a8.47 8.47 0 1 0 0-16.94a8.47 8.47 0 0 0 0 16.94");
}

.umeew3kms {
  d: path("M14.574 10.264v-.005c-.127.37-.43 1.297-.673 2.065c-.736 2.165-1.583 2.853-1.9 2.853c-.344 0-1.154-.688-1.906-2.858l-.434-1.366l-1.033-3.156a.5.5 0 0 1 .18-.031c.599 0 1.15.974 1.885 2.265l.355.625l.212.397c.29.556.518.932.74.948c.223-.016.45-.392.742-.953l.212-.392l.354-.625c.736-1.291 1.287-2.265 1.885-2.265q.097 0 .185.031zm.217.742c.217.773.47 1.773.518 2.35c.054.514.106 1.017.16 1.387c.036.27.264.466.54.466h1.593a.22.22 0 0 0 .222-.249c-.318-2.16-1.07-5.823-2.065-6.893l-.968 2.944zm-8.614 3.96c.318-2.166 1.075-5.834 2.075-6.899L9.211 11c-.212.779-.472 1.78-.52 2.361a40 40 0 0 1-.158 1.387a.54.54 0 0 1-.54.466H6.4a.22.22 0 0 1-.17-.072a.22.22 0 0 1-.053-.176");
}

</style>
