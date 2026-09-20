<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0t211bug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b0t211bug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-transfer-horizontal-bold" /></template>
