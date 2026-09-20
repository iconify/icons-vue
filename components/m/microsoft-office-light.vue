<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rd7hg6b0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rd7hg6b0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-office-light" /></template>
