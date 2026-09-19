<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tum1hdh1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tum1hdh1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:planet" /></template>
