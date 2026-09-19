<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq-489bvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cq-489bvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:scene-concentrate" /></template>
