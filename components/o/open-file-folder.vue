<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="p2ywf7bii"/><path class="pcqsdh9wj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:open-file-folder" /></template>
<style>
.p2ywf7bii {
  fill: var(--svg-color--269, #269);
  d: path("M0 29a4 4 0 0 0 4 4h24a4 4 0 0 0 4-4V12a4 4 0 0 0-4-4h-9c-3.562 0-3-5-8.438-5H4a4 4 0 0 0-4 4z");
}

.pcqsdh9wj {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M32.336 12h-6.562c-5.438 0-5.383 5-8.945 5h-9c-2.209 0-4.182 1.791-4.406 4l-.493 3.874L2.406 29l-.02-.002c-.116.607-.672.999-1.3.999c-.643 0-1.106-.507-1.074-1.144C.01 28.903 0 28.95 0 29a3.99 3.99 0 0 0 3.4 3.939c.177.038.371.061.6.061h26c2.209 0 4.182-1.791 4.406-4l1.523-13c.225-2.209-1.384-4-3.593-4");
}

</style>
