<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lord9gbjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lord9gbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ruler-2-off" /></template>
