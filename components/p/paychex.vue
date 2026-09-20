<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl7u15blk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bl7u15blk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:paychex" /></template>
