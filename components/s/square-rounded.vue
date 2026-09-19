<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq9x88bik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tq9x88bik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:square-rounded" /></template>
