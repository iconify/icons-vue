<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crev81m-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="crev81m-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-wearing-helmet-padding-raft" /></template>
