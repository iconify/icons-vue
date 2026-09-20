<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmj5--bma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmj5--bma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:projector-fill" /></template>
