<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/por-t0dql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="por-t0dql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:summation-02" /></template>
