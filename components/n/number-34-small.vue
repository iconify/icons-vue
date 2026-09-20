<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqtabzbbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqtabzbbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-34-small" /></template>
