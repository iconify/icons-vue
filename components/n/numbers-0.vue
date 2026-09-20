<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyqo3pdxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pyqo3pdxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:numbers-0" /></template>
