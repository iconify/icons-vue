<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci3qqtbba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ci3qqtbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-flag" /></template>
