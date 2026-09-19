<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr6q3nn4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kr6q3nn4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:smart-watch-filled" /></template>
