<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tknvn0cnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tknvn0cnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:snapcast-light" /></template>
