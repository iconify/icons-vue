<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srgj4acki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="srgj4acki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:shirt" /></template>
