<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhq2gxb7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nhq2gxb7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:xibo-light" /></template>
