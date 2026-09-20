<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlnsqdbzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rlnsqdbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:more-muted-horiz-circle-fill" /></template>
