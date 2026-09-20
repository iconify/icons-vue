<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygcac9taj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ygcac9taj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:revel-light" /></template>
