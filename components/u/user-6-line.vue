<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd526em5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bd526em5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:user-6-line" /></template>
