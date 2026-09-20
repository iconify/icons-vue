<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gei358h8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gei358h8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:unimus-dark" /></template>
