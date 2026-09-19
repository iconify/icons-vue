<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bj572-jhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bj572-jhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:wine-glass-outline" /></template>
