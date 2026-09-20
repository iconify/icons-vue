<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/suxzk1n9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="suxzk1n9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:minaret" /></template>
