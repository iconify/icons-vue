<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uafs1acwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uafs1acwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:passbolt-light" /></template>
