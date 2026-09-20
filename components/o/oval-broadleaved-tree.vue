<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp4ro4bdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xp4ro4bdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:oval-broadleaved-tree" /></template>
