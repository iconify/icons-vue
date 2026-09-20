<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qeuowkzon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qeuowkzon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sortifyr-dark" /></template>
