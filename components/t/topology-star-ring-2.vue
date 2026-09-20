<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq5aii1hg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lq5aii1hg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:topology-star-ring-2" /></template>
