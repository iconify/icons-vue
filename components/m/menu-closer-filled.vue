<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2vh03bjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2vh03bjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:menu-closer-filled" /></template>
