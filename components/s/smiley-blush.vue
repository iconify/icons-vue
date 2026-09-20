<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2ztgtcnl.css';
import '../../css/o/omzx56fzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2ztgtcnl"/><path class="omzx56fzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:smiley-blush" /></template>
