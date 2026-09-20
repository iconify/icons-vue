<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lswo68b0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lswo68b0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:moq" /></template>
