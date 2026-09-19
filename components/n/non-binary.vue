<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2lhzhbgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2lhzhbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:non-binary" /></template>
