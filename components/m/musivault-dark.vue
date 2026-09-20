<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugmjhhbyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ugmjhhbyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:musivault-dark" /></template>
