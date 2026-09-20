<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6qq-91sq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e6qq-91sq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:thumb-down-filled" /></template>
