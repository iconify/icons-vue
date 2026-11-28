<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz_f3g4jq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xz_f3g4jq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:speaker" /></template>
