<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnalu2bir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bnalu2bir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:virus-off" /></template>
