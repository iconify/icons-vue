<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrw4lrb7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rrw4lrb7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:stairs-descend-bold" /></template>
