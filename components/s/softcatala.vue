<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghd_tacsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghd_tacsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:softcatala" /></template>
