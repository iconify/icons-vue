<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzb3qybbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzb3qybbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:source-branch-sync" /></template>
