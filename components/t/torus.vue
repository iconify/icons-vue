<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tk-pp3bfw.css';
import '../../css/f/f3zm4_bki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tk-pp3bfw"/><path class="f3zm4_bki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:torus" /></template>
