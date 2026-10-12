<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s47ll6kkm.css';
import '../../css/j/j-aqdhbtt.css';
import '../../css/j/jgh0owb4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s47ll6kkm"/><path class="j-aqdhbtt"/><path class="jgh0owb4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:square-grid-circle-fill-20" /></template>
