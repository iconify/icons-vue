<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxi0a1bqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxi0a1bqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:user-alt-2-line" /></template>
