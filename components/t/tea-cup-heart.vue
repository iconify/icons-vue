<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bte9woctn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bte9woctn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:tea-cup-heart" /></template>
