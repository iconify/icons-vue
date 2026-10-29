<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8j5tt9nv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8j5tt9nv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:shield-check-solid" /></template>
