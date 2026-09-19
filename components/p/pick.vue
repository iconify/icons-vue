<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ncqzlr9tb"/><path class="e4ma7jbxx"/><path class="yrcbcz9dk"/><path class="lwr68ublo"/><path class="z513vx_fx"/><path class="brrb4abhg"/><path class="gl00ddcpl"/><path class="pym1ux8cx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:pick" /></template>
<style>
.brrb4abhg {
  fill: var(--svg-color--a6aeb2, #a6aeb2);
  d: path("M21.9 21.9C33.1 10.7 45.8 4.1 54.8 4.1C46.6-.4 31.1 5.4 18.3 18.2C5.4 31.1-.4 46.6 4.1 54.7c0-8.9 6.6-21.6 17.8-32.8");
}

.e4ma7jbxx {
  fill: var(--svg-color--ad8366, #ad8366);
  d: path("M56 60.6c1.6 1.7 6.3-3 4.7-4.7L24.5 19.8l-4.7 4.7z");
}

.gl00ddcpl {
  fill: var(--svg-color--5c6368, #5c6368);
  d: path("M27.7 15c.9.9.9 2.3 0 3.2l-9.6 9.6c-.9.9-2.3.9-3.2 0L10.1 23c-.9-.9-.9-2.3 0-3.2l9.6-9.6c.9-.9 2.3-.9 3.2 0z");
}

.lwr68ublo {
  fill: var(--svg-color--ad8366, #ad8366);
  d: path("M9.2 13.8c-1.7-1.6 3-6.3 4.7-4.7l6.2 6.2l-4.7 4.7z");
}

.ncqzlr9tb {
  fill: var(--svg-color--89664c, #89664c);
  d: path("M55.2 61.5c2.3 2.3 8.6-4 6.3-6.3L25.3 19L19 25.3z");
}

.pym1ux8cx {
  fill: var(--svg-color--474d51, #474d51);
  d: path("M26.3 15.9c.8.8.8 2 .1 2.7l-7.9 7.9c-.7.7-2 .7-2.7-.1L11.6 22c-.8-.8-.8-2-.1-2.7l7.9-7.8c.7-.7 2-.7 2.7.1z");
}

.yrcbcz9dk {
  fill: var(--svg-color--89664c, #89664c);
  d: path("M8.3 14.6c-2.3-2.3 4-8.6 6.3-6.3l6.2 6.2l-6.3 6.3z");
}

.z513vx_fx {
  fill: var(--svg-color--94989b, #94989b);
  d: path("M20.9 20.9C32.1 9.7 45.2 3.5 54.8 4.1c-9-5.3-25.2-.2-38 12.7c-12.9 12.8-18 29-12.7 38c-.6-9.6 5.6-22.7 16.8-33.9");
}

</style>
