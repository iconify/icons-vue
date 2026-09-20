<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do3yepbjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="do3yepbjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:voice-cricle" /></template>
