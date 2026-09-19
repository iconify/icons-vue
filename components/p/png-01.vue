<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4dtfzzcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4dtfzzcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:png-01" /></template>
