<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfrpoo3dn.css';
import '../../css/t/t_qou-ite.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfrpoo3dn"/><path class="t_qou-ite"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:zoom-out" /></template>
