<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zoe_q5b2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zoe_q5b2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:whitesource-logo-2-block" /></template>
