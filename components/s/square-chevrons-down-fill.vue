<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqzxtj6br.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqzxtj6br"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-chevrons-down-fill" /></template>
