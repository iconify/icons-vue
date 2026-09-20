<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3ls2vrqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c3ls2vrqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mautic-dark" /></template>
