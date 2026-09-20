<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6jndybtz.css';
import '../../css/o/ocih1mz8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6jndybtz"/><path class="ocih1mz8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:network-browser-bold" /></template>
