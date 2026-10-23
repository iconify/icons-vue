<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzk3koblg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzk3koblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:signal-medium" /></template>
