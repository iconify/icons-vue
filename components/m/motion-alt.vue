<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/koe8k3bmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="koe8k3bmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:motion-alt" /></template>
