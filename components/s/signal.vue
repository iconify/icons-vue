<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7_-a7ixx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7_-a7ixx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:signal" /></template>
