<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/posvzlbni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="posvzlbni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:water-bottle-1" /></template>
