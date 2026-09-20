<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xk54-pk0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xk54-pk0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:spacing-small-24" /></template>
