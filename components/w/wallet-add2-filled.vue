<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox9uvpbrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ox9uvpbrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:wallet-add2-filled" /></template>
