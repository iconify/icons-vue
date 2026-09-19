<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdwbaegjf.css';
import '../../css/g/g8gex4kkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdwbaegjf"/><path class="g8gex4kkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:volume-outlined" /></template>
