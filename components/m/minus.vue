<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn1qe8dtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="pn1qe8dtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:minus" /></template>
