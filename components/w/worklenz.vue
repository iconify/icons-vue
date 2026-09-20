<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsb9y4bou.css';
import '../../css/g/gwtyn9bdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dsb9y4bou"/><path class="gwtyn9bdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:worklenz" /></template>
