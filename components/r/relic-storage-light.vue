<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oor-few0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oor-few0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:relic-storage-light" /></template>
