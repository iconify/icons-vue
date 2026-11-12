<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hk8an_ymz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hk8an_ymz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:revel-light" /></template>
