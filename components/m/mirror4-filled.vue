<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg4wobcpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fg4wobcpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:mirror4-filled" /></template>
