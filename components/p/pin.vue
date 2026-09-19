<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy4414bsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zy4414bsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:pin" /></template>
