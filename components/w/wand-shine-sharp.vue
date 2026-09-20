<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqmd-dbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wand-shine-sharp" /></template>
<style>
.nqmd-dbzu {
  fill: currentColor;
  d: path("M8.66 7.398L6.37 5.11l.713-.714l2.289 2.289zm3.84-2.163v-3.25h1v3.25zm6.39 12.394l-2.288-2.289l.714-.713l2.288 2.289zM17.7 7.014l-.713-.714l2.288-2.288l.714.713zm1.066 4.486v-1h3.25v1zM5.728 21.079l-2.827-2.827l9.089-9.088q.586-.587 1.413-.587t1.413.587t.587 1.413t-.587 1.414zm6.275-7.677l2.1-2.125q.3-.3.3-.7t-.3-.7q-.281-.28-.7-.28t-.7.28l-2.125 2.125z");
}

</style>
