<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpe5don3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpe5don3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:peppers" /></template>
