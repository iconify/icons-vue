<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb403j67l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zb403j67l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shuffle-outline" /></template>
