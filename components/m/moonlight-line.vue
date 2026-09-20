<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cc-xlvwvo.css';
import '../../css/q/qsgxnsjgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cc-xlvwvo"/><path class="qsgxnsjgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:moonlight-line" /></template>
