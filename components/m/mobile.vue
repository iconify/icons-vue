<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti7py9bab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ti7py9bab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:mobile" /></template>
