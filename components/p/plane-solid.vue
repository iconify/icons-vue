<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldu42lbpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldu42lbpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:plane-solid" /></template>
