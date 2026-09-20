<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ib8c9xnsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ib8c9xnsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:trowel" /></template>
