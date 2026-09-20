<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-303cb4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-303cb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:stethoscope" /></template>
