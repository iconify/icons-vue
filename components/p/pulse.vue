<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psd2cpt5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="psd2cpt5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:pulse" /></template>
