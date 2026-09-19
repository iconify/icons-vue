<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aibc4p2_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aibc4p2_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:observation-24px" /></template>
