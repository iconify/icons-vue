<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzmlseboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tzmlseboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:post-content-light" /></template>
