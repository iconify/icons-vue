<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnrsrt4wg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qnrsrt4wg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-warning-fill" /></template>
