<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmhaztb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nmhaztb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:subtrackr-dark" /></template>
