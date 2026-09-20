<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txe6li42a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="txe6li42a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sort-alphabetical-ascending" /></template>
