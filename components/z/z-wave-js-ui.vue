<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jn4gi9b9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jn4gi9b9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:z-wave-js-ui" /></template>
