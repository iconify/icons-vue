<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo3thh0oo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo3thh0oo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:triangle-warning-round" /></template>
