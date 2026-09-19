<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p56h_bbeb.css';
import '../../css/p/p0qajccag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p56h_bbeb"/><path class="p0qajccag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:message-edit" /></template>
