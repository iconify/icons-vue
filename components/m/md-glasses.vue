<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghbtsdbdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ghbtsdbdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-glasses" /></template>
