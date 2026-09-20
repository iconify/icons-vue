<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxxxt8_4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gxxxt8_4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:pixabay-logo-block" /></template>
