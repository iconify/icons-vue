<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksjm_nbrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ksjm_nbrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:slideshow-fill" /></template>
