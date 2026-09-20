<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-b0mvb5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-b0mvb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:maintenance" /></template>
