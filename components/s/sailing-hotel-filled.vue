<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4aoocbil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4aoocbil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:sailing-hotel-filled" /></template>
