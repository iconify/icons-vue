<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8h8q4bhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8h8q4bhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-chevrons-right-filled" /></template>
