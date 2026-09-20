<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apmey5ikj.css';
import '../../css/r/rn5l7u0ji.css';
import '../../css/q/qmx_0jbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apmey5ikj"/><path class="rn5l7u0ji"/><path class="qmx_0jbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:rocket-5" /></template>
