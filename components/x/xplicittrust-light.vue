<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3jvbdb-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x3jvbdb-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:xplicittrust-light" /></template>
