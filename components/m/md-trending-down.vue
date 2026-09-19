<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jq3z381fk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jq3z381fk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-trending-down" /></template>
