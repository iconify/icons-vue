<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy48pgb-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sy48pgb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:shield-cross" /></template>
