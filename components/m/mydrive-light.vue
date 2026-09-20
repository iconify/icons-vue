<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm7abtb6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vm7abtb6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mydrive-light" /></template>
