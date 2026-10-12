<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsfs60bql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dsfs60bql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-arrow-down-right-filled" /></template>
