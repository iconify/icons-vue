<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpx5xid-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpx5xid-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:user-clock" /></template>
