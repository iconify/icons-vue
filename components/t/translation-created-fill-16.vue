<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cut4v5iaq.css';
import '../../css/l/l4i1co0oc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cut4v5iaq"/><path class="l4i1co0oc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:translation-created-fill-16" /></template>
