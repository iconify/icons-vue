<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-lfa9yzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-lfa9yzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:minimize-outline" /></template>
