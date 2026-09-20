<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syw-ieqgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="syw-ieqgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:picpeak" /></template>
