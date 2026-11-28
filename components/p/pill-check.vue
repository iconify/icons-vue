<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qircv0fuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qircv0fuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:pill-check" /></template>
