<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4ywnwb3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4ywnwb3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:pro" /></template>
