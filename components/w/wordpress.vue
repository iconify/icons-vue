<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dh-63tbow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dh-63tbow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:wordpress" /></template>
