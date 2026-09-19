<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g15bgfkmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g15bgfkmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:table" /></template>
