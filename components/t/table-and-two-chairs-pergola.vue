<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9gm-41sf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k9gm-41sf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:table-and-two-chairs-pergola" /></template>
