<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha9sq_r2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ha9sq_r2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:thumbs-up" /></template>
