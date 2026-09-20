<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7hhx-tpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7hhx-tpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:sun-24" /></template>
