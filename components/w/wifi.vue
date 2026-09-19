<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7fnzjw5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7fnzjw5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:wifi" /></template>
