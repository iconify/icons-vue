<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cir9vabuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cir9vabuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pencil-circle-filled" /></template>
