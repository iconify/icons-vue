<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1_ibvt6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1_ibvt6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:typescript-02" /></template>
