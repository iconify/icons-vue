<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m18fk9bwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":528,"height":448};
const content = `<path class="m18fk9bwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:water-temperature-30" /></template>
