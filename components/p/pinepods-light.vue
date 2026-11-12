<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlam0wbif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dlam0wbif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pinepods-light" /></template>
