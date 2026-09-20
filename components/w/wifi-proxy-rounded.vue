<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blvpuccif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wifi-proxy-rounded" /></template>
<style>
.blvpuccif {
  fill: currentColor;
  d: path("M16.808 18.635h1.769v-1.77h-1.77zm0-2.654h1.769v-1.77h-1.77zm2.653 2.653h1.77v-1.769h-1.77zm-2.615.885q-.384 0-.654-.269t-.269-.654V14.25q0-.385.27-.654t.653-.269h1.693q.384 0 .653.27t.27.653v1.73h1.73q.385 0 .654.27t.27.654v1.692q0 .385-.27.654t-.654.27zm-5.366-.608q-.24-.094-.44-.294l-8.292-8.292q-.248-.248-.37-.556q-.12-.307-.12-.636q0-.367.156-.714q.157-.347.492-.592q2.008-1.398 4.318-2.112T11.997 5t4.776.715t4.317 2.107q.34.222.506.57q.166.349.166.716q0 .329-.131.649t-.379.568l-.192.192q-.135.142-.328.192t-.38-.011q-.385-.117-.795-.176t-.82-.058q-2.421 0-4.123 1.701t-1.702 4.124q0 .41.058.82t.176.795q.056.186.006.379t-.186.328q-.206.206-.446.3q-.24.093-.52.093t-.52-.094");
}

</style>
