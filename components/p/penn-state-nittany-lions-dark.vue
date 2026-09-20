<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bim1nbclp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bim1nbclp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:penn-state-nittany-lions-dark" /></template>
