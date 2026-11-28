<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg-3gzbhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xg-3gzbhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:unlock-check" /></template>
