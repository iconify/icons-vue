<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii0e4j_mh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ii0e4j_mh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:satellite-antenna" /></template>
