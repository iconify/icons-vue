<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb3gzholy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cb3gzholy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wrtag-light" /></template>
