<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mte_34_1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mte_34_1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:up-small-line" /></template>
