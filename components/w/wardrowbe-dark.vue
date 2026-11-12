<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csj5fll6c.css';
import '../../css/y/y_bc29brb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="csj5fll6c"/><path class="y_bc29brb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wardrowbe-dark" /></template>
