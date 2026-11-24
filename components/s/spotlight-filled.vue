<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfsld5xui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfsld5xui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:spotlight-filled" /></template>
