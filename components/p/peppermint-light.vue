<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyyypq67t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kyyypq67t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:peppermint-light" /></template>
