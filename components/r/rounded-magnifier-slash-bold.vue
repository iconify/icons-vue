<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pq5k-cbtl.css';
import '../../css/o/opdy_4y2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pq5k-cbtl"/><path clip-rule="evenodd" class="opdy_4y2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rounded-magnifier-slash-bold" /></template>
