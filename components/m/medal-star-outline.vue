<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzs94db-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xzs94db-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:medal-star-outline" /></template>
