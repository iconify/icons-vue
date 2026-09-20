<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/paku0sb4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="paku0sb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:memorial" /></template>
