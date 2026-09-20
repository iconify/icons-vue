<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/noigyud1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="noigyud1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:qui-dark" /></template>
