<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdhfqclbu.css';
import '../../css/r/rh-ehybjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rdhfqclbu"/><path class="rh-ehybjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:markstack-dark" /></template>
