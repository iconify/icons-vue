<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avj0nu6ns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="avj0nu6ns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:sidebar-simple-right" /></template>
