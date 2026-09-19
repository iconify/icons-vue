<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_rht5bvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_rht5bvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:more-horizontal-square-01" /></template>
