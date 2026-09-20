<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abbyiwbcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="abbyiwbcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:python-light" /></template>
