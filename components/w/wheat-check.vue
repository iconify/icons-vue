<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2v2f3_sh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2v2f3_sh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:wheat-check" /></template>
