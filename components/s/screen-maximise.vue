<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzzwuub0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dzzwuub0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:screen-maximise" /></template>
