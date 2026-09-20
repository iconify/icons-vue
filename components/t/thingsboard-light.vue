<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgow5u3ic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mgow5u3ic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:thingsboard-light" /></template>
