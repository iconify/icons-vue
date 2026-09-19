<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0gvfdben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h0gvfdben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:settings-adjust-horizontal" /></template>
