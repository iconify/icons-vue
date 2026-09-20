<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwtxsgbve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dwtxsgbve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nintendo-switch-light" /></template>
