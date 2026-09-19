<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ab_bnglml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1025};
const content = `<path class="ab_bnglml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:wizard" /></template>
