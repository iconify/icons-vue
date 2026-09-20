<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojldz2bdb.css';
import '../../css/e/ee089sbds.css';
import '../../css/o/os-6ceb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ojldz2bdb"/><path class="ee089sbds"/><path class="os-6ceb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:stirling-pdf-dark" /></template>
