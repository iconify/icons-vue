<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdjcw3-gp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdjcw3-gp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:mirror" /></template>
