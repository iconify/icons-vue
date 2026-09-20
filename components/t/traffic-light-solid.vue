<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvyskiz7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dvyskiz7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:traffic-light-solid" /></template>
