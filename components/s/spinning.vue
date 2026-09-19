<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvhzp_tdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvhzp_tdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:spinning" /></template>
