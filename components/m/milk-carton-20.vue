<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ht5i-fb7m.css';
import '../../css/p/pa8jkb1da.css';
import '../../css/c/cfktgscfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ht5i-fb7m"/><path class="pa8jkb1da"/><path class="cfktgscfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:milk-carton-20" /></template>
