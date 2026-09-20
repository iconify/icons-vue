<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6-y9-87l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l6-y9-87l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:merge" /></template>
