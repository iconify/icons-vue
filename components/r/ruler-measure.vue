<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcivn0byp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcivn0byp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ruler-measure" /></template>
