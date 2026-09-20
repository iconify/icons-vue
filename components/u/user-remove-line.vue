<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxnxe3krn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxnxe3krn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-remove-line" /></template>
