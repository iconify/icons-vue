<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gejohc1vg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gejohc1vg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:map-fill" /></template>
