<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lphe4gxwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lphe4gxwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:moon-outline" /></template>
