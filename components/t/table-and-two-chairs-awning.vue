<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpowmn5rd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xpowmn5rd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:table-and-two-chairs-awning" /></template>
