<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0n5t_msv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0n5t_msv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:presentation-analytics" /></template>
