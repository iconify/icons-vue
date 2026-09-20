<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igxg7ab5n.css';
import '../../css/n/ni2kd7y2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="igxg7ab5n"/><path class="ni2kd7y2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sunshine-light" /></template>
