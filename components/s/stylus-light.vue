<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5mrid3qd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o5mrid3qd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:stylus-light" /></template>
