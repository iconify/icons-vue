<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr5oj0o0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pr5oj0o0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:sidebar-unfold-fill" /></template>
