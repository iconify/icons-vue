<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2saefbgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2saefbgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:razor" /></template>
