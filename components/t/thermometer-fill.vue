<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzv0wwgxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jzv0wwgxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:thermometer-fill" /></template>
