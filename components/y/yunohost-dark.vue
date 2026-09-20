<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/voaf05beg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="voaf05beg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yunohost-dark" /></template>
