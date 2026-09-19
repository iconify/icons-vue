<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg50s5vtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gg50s5vtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:planet" /></template>
