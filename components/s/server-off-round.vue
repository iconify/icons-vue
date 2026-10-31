<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bj5ec_vnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bj5ec_vnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-off-round" /></template>
