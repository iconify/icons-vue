<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/baduyu46m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="baduyu46m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:modelcontextprotocol" /></template>
