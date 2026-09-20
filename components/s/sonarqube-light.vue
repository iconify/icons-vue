<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mx83neb9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mx83neb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sonarqube-light" /></template>
