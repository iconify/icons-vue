<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s43n5kbjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s43n5kbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:netvisor-light" /></template>
