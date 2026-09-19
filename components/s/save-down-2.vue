<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4f69cbip.css';
import '../../css/p/paxrevb-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4f69cbip"/><path class="paxrevb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:save-down-2" /></template>
