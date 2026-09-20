<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf_b-v1zy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kf_b-v1zy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:message-programming-filled" /></template>
