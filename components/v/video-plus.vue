<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/miovhmbbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="miovhmbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:video-plus" /></template>
