<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1z02kbki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="e1z02kbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:sos" /></template>
