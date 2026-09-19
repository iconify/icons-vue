<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui7t-jbzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ui7t-jbzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:menu-square" /></template>
