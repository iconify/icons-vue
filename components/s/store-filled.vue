<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q85ug49pp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="q85ug49pp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:store-filled" /></template>
