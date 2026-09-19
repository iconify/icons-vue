<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rca25moxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rca25moxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:plus" /></template>
