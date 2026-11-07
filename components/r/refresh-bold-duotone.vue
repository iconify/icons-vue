<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddb602buy.css';
import '../../css/z/z84lzbbag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddb602buy"/><path class="z84lzbbag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:refresh-bold-duotone" /></template>
