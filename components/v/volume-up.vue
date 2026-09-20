<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uby2awbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uby2awbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:volume-up" /></template>
