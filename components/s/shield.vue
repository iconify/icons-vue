<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyj7oveoi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyj7oveoi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:shield" /></template>
