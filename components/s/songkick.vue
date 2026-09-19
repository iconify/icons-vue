<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1a3womlm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a1a3womlm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:songkick" /></template>
