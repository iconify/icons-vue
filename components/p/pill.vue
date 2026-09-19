<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l98k7eboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l98k7eboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pill" /></template>
