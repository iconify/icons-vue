<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dr5mytb7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dr5mytb7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wash-machine-fill" /></template>
