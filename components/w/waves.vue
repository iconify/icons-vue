<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq-_nebdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lq-_nebdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:waves" /></template>
