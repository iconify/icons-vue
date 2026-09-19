<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irpme3b0m.css';
import '../../css/h/hetvd6utf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irpme3b0m"/><path class="hetvd6utf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:volume-off-fill" /></template>
