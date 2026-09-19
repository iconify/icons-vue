<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwcztmbcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="pwcztmbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:palfed" /></template>
