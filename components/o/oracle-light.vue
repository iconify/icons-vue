<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhbusi2cy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dhbusi2cy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:oracle-light" /></template>
