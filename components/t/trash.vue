<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w88yt2b8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w88yt2b8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:trash" /></template>
