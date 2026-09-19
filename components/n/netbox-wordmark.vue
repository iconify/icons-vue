<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4b5m0bco.css';
import '../../css/s/svf4jc_ce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="e4b5m0bco"/><path class="svf4jc_ce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:netbox-wordmark" /></template>
