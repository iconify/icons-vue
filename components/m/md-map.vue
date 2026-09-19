<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r01fabc7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r01fabc7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-map" /></template>
