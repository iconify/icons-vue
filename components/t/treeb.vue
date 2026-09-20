<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfdl7e5aj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dfdl7e5aj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:treeb" /></template>
