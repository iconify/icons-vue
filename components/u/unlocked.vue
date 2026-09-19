<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="fe1op8b0l"/><path class="ickzr_7kc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:unlocked" /></template>
<style>
.fe1op8b0l {
  fill: var(--svg-color--989897, #989897);
  d: path("M49.502 9.548c-8.488-10.835-25.48-11.12-35.348-2.272c-.99.883-1.15 2.405-.27 3.43c.548.644 1.092 1.286 1.646 1.929c.41.481.888.73 1.376.81c.653.176 1.39.063 2.06-.54C36.174-2.58 59.4 24.607 41.42 39.187c-1.031.838-1.115 2.445-.27 3.434q.83.967 1.647 1.927c.88 1.029 2.408 1.11 3.436.27c10.963-8.926 11.741-24.46 3.272-35.27");
}

.ickzr_7kc {
  fill: var(--svg-color--f79421, #f79421);
  d: path("M6.784 63h51.699c.43 0 .784-.258.784-.555v-35.75c0-.3-.353-.553-.784-.553H6.784c-.236 0-.414.057-.536.148c0 0-.009.009-.014.018c-.012 0-.017.004-.026.019a.43.43 0 0 0-.208.368v35.75c0 .297.357.555.784.555");
}

</style>
