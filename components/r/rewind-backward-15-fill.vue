<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wi1wpwtzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wi1wpwtzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rewind-backward-15-fill" /></template>
