<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfb1qvbtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bfb1qvbtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nodebb-light" /></template>
