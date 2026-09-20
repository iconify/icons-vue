<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azh1nvbrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="azh1nvbrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:tool" /></template>
