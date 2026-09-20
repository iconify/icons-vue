<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfs34wexj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stop-screen-share-outline-sharp" /></template>
<style>
.tfs34wexj {
  fill: currentColor;
  d: path("m14.021 11.171l-1.555-1.555h.803V8.308l1.808 1.808zm6.102 6.102l-.85-.85H20V5.462H8.312l-1-1H21v12.811zm1.07 5.335l-3.147-3.146H1.77v-1h15.272l-1-1H3V5.042h.615L1.392 2.808L2.1 2.1l19.8 19.8zM10.076 11.504q-.154.173-.23.356q-.078.182-.078.452v1.804h-1v-2q0-.468.15-.833q.15-.366.352-.59L4.48 5.902H4v10.56h11.035zm-.31-.335");
}

</style>
