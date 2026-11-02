<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2dixy0jy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2dixy0jy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sidebar-right-close-fill" /></template>
