<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uabj9zb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uabj9zb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:system-log-filled" /></template>
