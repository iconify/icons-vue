<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="x1wkitbuq"/><path class="y2mo_go8j"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:primal-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.x1wkitbuq {
  fill: var(--svg-color--fd2d3a, #fd2d3a);
  d: path("M24 0H0v24h24z");
}

.y2mo_go8j {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.129 15.702c.186.765-.231 2.547-.462 3.342c.848 0 2.875-.044 3.244-.24c.467-.235 1.627 0 2.089 0s1.622-.475 2.089-.475c.462 0 1.622.715 1.853.956c.187.19 1.005.08 1.391 0v-4.298c0-.627-.231-1.196-.231-1.912c0-.715.231-1.195.231-1.91c0-.574-.155-3.903-.231-5.494l-.929 3.582v-.955c-.155.24-.462.813-.462 1.195c0 .476-.698 2.387-.929 2.867c-.187.382-.542 2.707-.693 3.822a2.3 2.3 0 0 1-.236-.809c0-.329 0-.866-.23-.866c-.232 0 .23-.956.23-1.431c0-.48 0-1.436.236-1.912c.23-.48-.467-2.15-.934-2.626c-.368-.382-.613-3.187-.693-4.538c-.076 1.196-.275 3.724-.462 4.298c-.231.715-.698 1.91-.698 2.387c0 .48-.231 1.675-.231 2.39c0 .574-.151 1.352-.231 1.672c-.311-.8-.93-2.534-.93-3.107s-.31-1.35-.46-1.67l-.231 1.196L7.595 5.67c-.08 1.911-.23 5.924-.23 6.689c0 .956-.467 2.387-.236 3.342M6.667 20v-.445H15.2c.418 0 .742.112.853.223c.09.089.889.035 1.28 0V20c-.542-.036-1.724-.133-2.133-.222c-.511-.111-2.56.222-2.987.222c-.426 0-1.493-.222-1.92-.222c-.342 0-2.56.146-3.626.222");
}

</style>
