<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhn7erbyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xhn7erbyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:sidebar-expand-outline" /></template>
