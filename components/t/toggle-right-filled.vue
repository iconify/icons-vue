<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo1q0dvgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo1q0dvgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:toggle-right-filled" /></template>
