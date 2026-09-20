<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hy3jeobtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hy3jeobtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:reply-duotone" /></template>
