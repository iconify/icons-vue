<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j79e-tbuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j79e-tbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:sync-exclamation" /></template>
