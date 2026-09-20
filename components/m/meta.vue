<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqsn7cccf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="iqsn7cccf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:meta" /></template>
