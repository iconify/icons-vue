<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx9rzpk0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-1,"top":-1};
const content = `<path class="hx9rzpk0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:wrench" /></template>
