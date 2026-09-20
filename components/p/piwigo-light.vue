<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tin4jwbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tin4jwbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:piwigo-light" /></template>
