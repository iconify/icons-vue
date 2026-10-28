<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uu8klpb7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uu8klpb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:octagon-minus" /></template>
