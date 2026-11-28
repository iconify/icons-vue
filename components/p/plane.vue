<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ius8nukxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ius8nukxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:plane" /></template>
