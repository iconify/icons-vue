<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqfy69bax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqfy69bax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:temple-hindu-outline" /></template>
