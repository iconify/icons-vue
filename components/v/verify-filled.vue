<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk5d2mhzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qk5d2mhzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:verify-filled" /></template>
