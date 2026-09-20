<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uw2ai9btp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:photo-auto-merge-sharp" /></template>
<style>
.uw2ai9btp {
  fill: currentColor;
  d: path("M4.567 21.36L2.904 8.389l2.327-.247V18.77h13.096l.098.843zm2.664-4.59V3h7.625q-.2.404-.297.827t-.097.871q0 .529.143 1.077t.403 1.033q-.204-.116-.437-.173q-.233-.058-.456-.058q-1.015 0-1.729.716t-.713 1.726q0 1.016.713 1.729t1.73.714q.98 0 1.682-.673t.748-1.654q0-.154-.038-.308l-.077-.308q.592.452 1.292.672q.7.219 1.425.219q.48 0 .945-.09q.465-.091.907-.291v7.74zm1.577-1h10.615v-.186q-1.067-1.088-2.434-1.682t-2.873-.594q-1.512 0-2.876.594q-1.365.594-2.432 1.683zm8.463-8.943l1.468-4.115h.85l1.473 4.115h-.768l-.317-.87h-1.646l-.279.87zm1.271-1.465h1.243l-.631-1.974z");
}

</style>
