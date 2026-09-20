<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nk-tvyzxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nk-tvyzxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:test-pipe-2" /></template>
