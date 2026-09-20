<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0rns4bdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a0rns4bdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vykar" /></template>
