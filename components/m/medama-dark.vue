<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezsvxzzya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ezsvxzzya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:medama-dark" /></template>
