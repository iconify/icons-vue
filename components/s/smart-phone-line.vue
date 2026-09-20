<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nczf77b0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nczf77b0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:smart-phone-line" /></template>
