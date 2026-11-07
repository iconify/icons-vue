<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxcvi3b3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxcvi3b3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:test-tube-minimalistic-broken" /></template>
