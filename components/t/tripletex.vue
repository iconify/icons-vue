<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ars0csbok.css';
import '../../css/w/wuxne-bcb.css';
import '../../css/o/owmyuv0ev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25.9,"height":38};
const content = `<path class="ars0csbok"/><path class="wuxne-bcb"/><path class="owmyuv0ev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:tripletex" /></template>
