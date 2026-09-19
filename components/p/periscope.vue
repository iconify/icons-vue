<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7pm8bbki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="s7pm8bbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:periscope" /></template>
