<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkahdjavk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zkahdjavk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:matrix" /></template>
