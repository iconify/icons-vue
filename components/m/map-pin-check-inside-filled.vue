<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bga350_7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bga350_7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:map-pin-check-inside-filled" /></template>
