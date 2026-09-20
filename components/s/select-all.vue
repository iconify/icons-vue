<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s115isbjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s115isbjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:select-all" /></template>
