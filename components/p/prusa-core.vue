<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pel2tfbsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pel2tfbsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:prusa-core" /></template>
