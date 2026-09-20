<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/juf74mb5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="juf74mb5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:other-ui-send" /></template>
