<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjw-5hb7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjw-5hb7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:shield-down-solid" /></template>
