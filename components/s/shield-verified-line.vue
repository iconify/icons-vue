<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmja12b5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmja12b5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:shield-verified-line" /></template>
