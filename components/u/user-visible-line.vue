<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krnl832ox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krnl832ox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-visible-line" /></template>
