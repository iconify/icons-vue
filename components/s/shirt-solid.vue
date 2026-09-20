<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0mgmxb1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c0mgmxb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:shirt-solid" /></template>
