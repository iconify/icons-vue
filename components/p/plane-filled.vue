<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca_8f2b4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ca_8f2b4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:plane-filled" /></template>
