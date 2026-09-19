<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kp0-zh71n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kp0-zh71n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:princess-auto" /></template>
