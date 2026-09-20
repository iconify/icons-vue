<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt822uk-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nt822uk-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:maintenance-square" /></template>
