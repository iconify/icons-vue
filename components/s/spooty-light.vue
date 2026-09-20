<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyp808bel.css';
import '../../css/g/gq1c8db9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uyp808bel"/><path class="gq1c8db9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:spooty-light" /></template>
