<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rs40jpbkq.css';
import '../../css/r/r5w09bcrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rs40jpbkq"/><path class="r5w09bcrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:note-pencil-stroke-20" /></template>
