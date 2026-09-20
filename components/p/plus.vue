<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvqgy2b5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xvqgy2b5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:plus" /></template>
