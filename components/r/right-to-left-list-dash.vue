<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xar84slld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xar84slld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:right-to-left-list-dash" /></template>
