<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwoh2zb5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwoh2zb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:police-car-1" /></template>
