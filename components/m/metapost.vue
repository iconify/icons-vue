<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_l-zdltb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u_l-zdltb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:metapost" /></template>
