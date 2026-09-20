<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nf4wu4gsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nf4wu4gsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:package-down" /></template>
