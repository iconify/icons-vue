<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7_aqub-c.css';
import '../../css/t/tcimq1bdm.css';
import '../../css/x/x3wytyg0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><clipPath id="SVGrR3hXb3H"><path class="f7_aqub-c"/></clipPath></defs><g clip-path="url(#SVGrR3hXb3H)"><path class="tcimq1bdm"/></g><path class="x3wytyg0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:sema-wordmark" /></template>
