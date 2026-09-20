<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sujsk-bgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sujsk-bgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:text-formating-arrange-spacing" /></template>
