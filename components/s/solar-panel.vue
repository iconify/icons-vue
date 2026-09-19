<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2gdm3bzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2gdm3bzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:solar-panel" /></template>
