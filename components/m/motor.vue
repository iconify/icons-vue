<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qn6gtwqvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qn6gtwqvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:motor" /></template>
