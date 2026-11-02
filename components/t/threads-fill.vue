<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctkfd1bkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctkfd1bkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:threads-fill" /></template>
