<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejpz3s0yd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejpz3s0yd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:plus-big-filled" /></template>
