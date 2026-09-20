<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgp-djbme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rgp-djbme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:powerdns" /></template>
