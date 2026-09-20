<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9-dtpbua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q9-dtpbua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:velero-dark" /></template>
