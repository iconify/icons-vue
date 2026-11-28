<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf9tlotji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pf9tlotji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:rotate-ccw-solid" /></template>
