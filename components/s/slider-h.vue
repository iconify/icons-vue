<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu5j-eb8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gu5j-eb8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:slider-h" /></template>
