<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b288o1b6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b288o1b6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:staircase-down-2" /></template>
