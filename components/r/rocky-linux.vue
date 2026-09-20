<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgiw3fv-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgiw3fv-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:rocky-linux" /></template>
