<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/my03x_qnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="my03x_qnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:volume-mute" /></template>
