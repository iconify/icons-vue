<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2e2b28aw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2e2b28aw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:menu-line" /></template>
