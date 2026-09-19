<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcm8htdvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcm8htdvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:scroll-filled" /></template>
