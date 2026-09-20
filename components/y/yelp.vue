<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8pyclbov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p8pyclbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yelp" /></template>
