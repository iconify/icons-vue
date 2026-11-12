<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wddu7jbzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wddu7jbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:seelf-dark" /></template>
