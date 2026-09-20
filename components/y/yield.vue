<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmt69hb5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nmt69hb5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:yield" /></template>
