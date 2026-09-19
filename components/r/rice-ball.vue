<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="fg4iddcxx"/><path class="b1udkib7s"/><path class="lnvwn-b-s"/><path class="qwf_clilg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:rice-ball" /></template>
<style>
.b1udkib7s {
  fill: var(--svg-color--d2d8d9, #d2d8d9);
  d: path("M50.4 35c-7.5-1.9-9.2 3.5-1.7 5.5s9.2-3.6 1.7-5.5m4.4 12c-5.5-5.4-9.7-1.6-4.2 3.9s9.8 1.5 4.2-3.9M42.6 24.8c-3.1 7 1.9 9.6 5.1 2.6c3.3-7-1.9-9.7-5.1-2.6M37 17.1c-7.1-3-9.6 2.1-2.5 5.2c7.1 3.2 9.6-2.2 2.5-5.2M30.1 6.6c-7.2 2.7-5.5 8.1 1.8 5.5c7.3-2.7 5.4-8.2-1.8-5.5m-7.9 13.2c-6.5-4-9.8.6-3.3 4.7c6.6 4.2 9.9-.7 3.3-4.7m8.1 7.7c-7.4 2.1-6.2 7.6 1.3 5.6s6.1-7.7-1.3-5.6M12.5 31c-6.8 3.5-4.6 8.7 2.3 5.3c7-3.5 4.6-8.9-2.3-5.3m-1.3 15c-7.4-2.2-9.3 3.1-2 5.4c7.5 2.3 9.4-3.2 2-5.4");
}

.fg4iddcxx {
  fill: var(--svg-color--e6eded, #e6eded);
  d: path("M57.1 36.2c1.2-4.3-3.5-10.6-6-12.1c-.8-10.1-6.6-11-6.6-11c-6.6-14.8-18.5-14.8-25 0c0 0-5.9.9-6.6 11c-2.5 1.6-7.2 7.8-6 12.1C1.3 40 .7 50.5 4.2 51.4C2 62.9 62 62.9 59.8 51.4c3.6-.9 2.9-11.3-2.7-15.2");
}

.lnvwn-b-s {
  fill: var(--svg-color--334037, #334037);
  d: path("M47 59.8c0 2.9-30 2.9-30 0V36h30z");
}

.qwf_clilg {
  fill: var(--svg-color--3f4f44, #3f4f44);
  d: path("m20.6 47.1l-1 1.6l1 1.5l1-1.5zm11.4 0l-1 1.6l1 1.5l1-1.5zm11.4 0l-1 1.6l1 1.5l1-1.5zm-22.8-9.3l-1 1.5l1 1.6l1-1.6zm11.4 0l-1 1.5l1 1.6l1-1.6zm11.4 0l-1 1.5l1 1.6l1-1.6zM20.6 56.5l-1 1.5l1 1.6l1-1.6zm11.4 0L31 58l1 1.6l1-1.6zm11.4 0l-1 1.5l1 1.6l1-1.6zm-5.7-4.7l-1 1.6l1 1.5l1-1.5zm-11.4 0l-1 1.6l1 1.5l1-1.5zm11.4-9.3l-1 1.5l1 1.6l1-1.6zm-11.4 0l-1 1.5l1 1.6l1-1.6z");
}

</style>
