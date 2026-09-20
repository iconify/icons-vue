<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2zno77vb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2.5,"top":-6};
const content = `<path class="i2zno77vb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:switch-right-f" /></template>
