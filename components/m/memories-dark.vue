<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sknrdgbnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sknrdgbnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:memories-dark" /></template>
