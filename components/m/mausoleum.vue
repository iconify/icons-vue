<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdn95mbqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sdn95mbqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:mausoleum" /></template>
