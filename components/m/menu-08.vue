<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3rvv1bds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3rvv1bds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:menu-08" /></template>
