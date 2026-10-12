<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slb2x7b6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slb2x7b6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:skip-forward-filled" /></template>
