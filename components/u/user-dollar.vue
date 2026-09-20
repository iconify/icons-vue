<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwof7pjvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwof7pjvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:user-dollar" /></template>
