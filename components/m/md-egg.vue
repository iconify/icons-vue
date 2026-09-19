<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilf5-qrkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ilf5-qrkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-egg" /></template>
