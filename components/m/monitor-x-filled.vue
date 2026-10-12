<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-l6sbc0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t-l6sbc0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:monitor-x-filled" /></template>
