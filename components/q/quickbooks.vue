<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0p98cbaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0p98cbaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:quickbooks" /></template>
