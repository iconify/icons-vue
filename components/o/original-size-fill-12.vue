<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5z1758ht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="z5z1758ht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:original-size-fill-12" /></template>
