<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltj29ibgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ltj29ibgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opensuse-step-dark" /></template>
