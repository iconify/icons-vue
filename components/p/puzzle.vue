<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/as6u8f6hn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="as6u8f6hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:puzzle" /></template>
