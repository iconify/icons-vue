<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thbt_3blk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thbt_3blk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mail-volume-fill" /></template>
