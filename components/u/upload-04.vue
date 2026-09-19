<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9fx60lvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9fx60lvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:upload-04" /></template>
