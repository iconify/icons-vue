<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nawkj_bvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nawkj_bvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pencil-off" /></template>
