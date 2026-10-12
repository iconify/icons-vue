<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sudnoc56x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sudnoc56x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:text-read-aloud" /></template>
