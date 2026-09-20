<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5_26y1bs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5_26y1bs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:paint-filled" /></template>
