<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr1266b5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gr1266b5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:refresh-circle-bold" /></template>
