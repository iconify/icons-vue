<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfnb6qb_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfnb6qb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sidebar-right-open-line" /></template>
