<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bph8-725u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bph8-725u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:signal-6g" /></template>
