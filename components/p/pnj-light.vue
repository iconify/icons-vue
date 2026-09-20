<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc--wpv5i.css';
import '../../css/z/zuyq0qy7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1510,"height":1515};
const content = `<defs><linearGradient id="SVGQXwgc7RF" x2="1" gradientTransform="rotate(-12 4465 426)scale(1466.69 1469.872)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient></defs><path fill="url(#SVGQXwgc7RF)" class="zuyq0qy7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pnj-light" /></template>
