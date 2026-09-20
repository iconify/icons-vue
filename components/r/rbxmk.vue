<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-jq0l3km.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r-jq0l3km"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:rbxmk" /></template>
