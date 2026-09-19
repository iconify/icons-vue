<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-p0k3n1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-p0k3n1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:skype" /></template>
