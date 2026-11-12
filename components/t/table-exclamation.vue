<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj9b9rbwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xj9b9rbwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:table-exclamation" /></template>
