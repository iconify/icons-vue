<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/maaver_gh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="maaver_gh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:movistar" /></template>
