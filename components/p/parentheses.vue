<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch4k0itjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ch4k0itjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:parentheses" /></template>
