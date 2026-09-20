<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_hx2l-ia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_hx2l-ia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:wave-lines" /></template>
