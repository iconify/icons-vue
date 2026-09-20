<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyle43bgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gyle43bgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sugar-coated-haws-fill" /></template>
