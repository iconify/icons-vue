<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zk4cshaty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zk4cshaty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:search-check" /></template>
