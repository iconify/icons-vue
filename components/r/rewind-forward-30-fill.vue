<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufwsjyb3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufwsjyb3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rewind-forward-30-fill" /></template>
