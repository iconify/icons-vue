<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/se6s0tb-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="se6s0tb-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sprout-solid" /></template>
