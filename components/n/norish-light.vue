<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmri_4b7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pmri_4b7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:norish-light" /></template>
