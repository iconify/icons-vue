<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un0pq6cid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="un0pq6cid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:rotate-rectangle" /></template>
