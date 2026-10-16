<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qu2vshdfm.css';
import '../../css/c/ctjzoy1eo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qu2vshdfm"/><path class="ctjzoy1eo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:semi-detached-48" /></template>
