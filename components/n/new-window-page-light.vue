<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw5f2fnxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zw5f2fnxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:new-window-page-light" /></template>
