<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cse8nbblk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cse8nbblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:set-all" /></template>
