<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnhu78nqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qnhu78nqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:sock-filled" /></template>
