<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gudpb6b2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gudpb6b2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:mouse-pointer-2-off" /></template>
