<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5fqd7-mo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5fqd7-mo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:samsung-serif-stand" /></template>
