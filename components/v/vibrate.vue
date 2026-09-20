<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pm1fd75xe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pm1fd75xe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:vibrate" /></template>
