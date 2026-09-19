<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmt_occ7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":548,"height":762};
const content = `<path class="tmt_occ7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:v-upper-case" /></template>
