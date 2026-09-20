<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-onlu_fk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u-onlu_fk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:velld-dark" /></template>
