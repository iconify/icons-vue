<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqwsjp3fu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fqwsjp3fu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:neutral-face-in-circle-outline" /></template>
