<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-8gb9b7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-8gb9b7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:mouse-pointer" /></template>
