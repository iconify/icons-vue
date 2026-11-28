<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxraj1upd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxraj1upd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:mug" /></template>
