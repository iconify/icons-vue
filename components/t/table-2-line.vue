<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v72m8yb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v72m8yb1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:table-2-line" /></template>
