<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1otxkt3x.css';
import '../../css/y/yic1v-1qv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1otxkt3x"/><path class="yic1v-1qv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:trees-filled" /></template>
