<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdzk9tywb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdzk9tywb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:undo" /></template>
