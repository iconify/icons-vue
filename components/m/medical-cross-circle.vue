<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_m9638xq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_m9638xq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:medical-cross-circle" /></template>
