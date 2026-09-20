<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkziq126x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkziq126x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:marketo" /></template>
