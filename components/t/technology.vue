<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_80r7goz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_80r7goz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:technology" /></template>
