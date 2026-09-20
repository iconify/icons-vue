<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4ku_18or.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b4ku_18or"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tag-horizontal-bold" /></template>
