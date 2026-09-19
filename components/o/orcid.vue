<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba_3tvb6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ba_3tvb6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:orcid" /></template>
