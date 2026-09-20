<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_ucf8jbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_ucf8jbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:user-received-line" /></template>
