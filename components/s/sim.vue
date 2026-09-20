<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxq6v60ur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bxq6v60ur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:sim" /></template>
