<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc78iibhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yc78iibhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:podcast-light" /></template>
