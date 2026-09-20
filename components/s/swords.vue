<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lczie4blv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lczie4blv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:swords" /></template>
