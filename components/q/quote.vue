<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iik18ybtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iik18ybtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:quote" /></template>
