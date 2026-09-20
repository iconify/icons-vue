<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmj9r3-wc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmj9r3-wc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:notification-3-fill" /></template>
