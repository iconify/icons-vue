<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpo_bc98z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xpo_bc98z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:precise-monitor" /></template>
