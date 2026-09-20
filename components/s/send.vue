<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/illv9zyxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="illv9zyxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:send" /></template>
