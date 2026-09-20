<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3r2ddc9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3r2ddc9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:signal-cellular-2-fill" /></template>
