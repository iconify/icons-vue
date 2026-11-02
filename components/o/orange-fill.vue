<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq9qfd_rt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uq9qfd_rt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:orange-fill" /></template>
