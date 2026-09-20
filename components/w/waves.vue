<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqfn82bnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqfn82bnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:waves" /></template>
