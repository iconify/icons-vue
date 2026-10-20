<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dco4-8bwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dco4-8bwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:user-round-check" /></template>
