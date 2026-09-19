<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa8ssc4_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xa8ssc4_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:raspberry-pi" /></template>
