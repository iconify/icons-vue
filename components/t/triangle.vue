<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s331_4brb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s331_4brb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:triangle" /></template>
