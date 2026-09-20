<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hekg713-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hekg713-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-wearing-helmet-paddling-raft-on-water" /></template>
