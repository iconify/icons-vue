<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhdzl1b5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vhdzl1b5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:passport-checkpoint" /></template>
