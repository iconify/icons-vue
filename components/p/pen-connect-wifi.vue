<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyx6_8qkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yyx6_8qkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:pen-connect-wifi" /></template>
