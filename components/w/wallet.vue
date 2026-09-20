<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjz9jgbbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjz9jgbbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:wallet" /></template>
