<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwy9mjn_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwy9mjn_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shapes-alt" /></template>
