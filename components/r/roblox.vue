<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmevz-btj.css';
import '../../css/o/oynab6bpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bmevz-btj"/><path class="oynab6bpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:roblox" /></template>
