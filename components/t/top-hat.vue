<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="etry_ab0y"/><path class="x-bunrbsj"/><path class="a2ezidb2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:top-hat" /></template>
<style>
.a2ezidb2i {
  fill: var(--svg-color--744eaa, #744eaa);
  d: path("m30.198 27.385l.446-5.829c-7.705 2.157-17.585 2.207-25.316-.377l.393 5.142c.069.304.113.65.113 1.076c0 1.75 1.289 2.828 2.771 3.396c4.458 1.708 13.958 1.646 18.807.149c1.467-.453 2.776-1.733 2.776-3.191c0-.119.015-.241.024-.361z");
}

.etry_ab0y {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M30.198 27.385L32 3.816a3 3 0 0 0-.021-.373c.003-.033.021-.075.021-.11C32 1.529 25.731.066 18 .066c-7.732 0-14 1.462-14 3.267c0 .035.017.068.022.102Q4.001 3.599 4 3.8l1.802 23.585C2.298 28.295 0 29.576 0 31c0 2.762 8.611 5 18 5s18-2.238 18-5c0-1.424-2.298-2.705-5.802-3.615");
}

.x-bunrbsj {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M17.536 6.595c-4.89 0-8.602-.896-10.852-1.646a1 1 0 1 1 .632-1.898c2.889.963 10.762 2.891 21.421-.016a1 1 0 1 1 .525 1.93c-4.406 1.202-8.347 1.63-11.726 1.63");
}

</style>
