<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxany_f2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxany_f2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:refresh-3-fill" /></template>
