<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqsb1e8mr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqsb1e8mr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:vk-alt" /></template>
