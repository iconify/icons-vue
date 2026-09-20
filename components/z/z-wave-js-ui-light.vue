<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngv76bsku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ngv76bsku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:z-wave-js-ui-light" /></template>
