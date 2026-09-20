<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuktf_bzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cuktf_bzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:upwork-fill" /></template>
