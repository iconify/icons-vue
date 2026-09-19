<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1ta7ccsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1ta7ccsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:phone-off-outline" /></template>
