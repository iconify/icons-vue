<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/s/sjxgbg2th.css';
import '../../css/t/tf3n6m1cy.css';
import '../../css/l/ljhemfwhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="sjxgbg2th wm-shadow"/><path class="tf3n6m1cy wm-shadow"/><path class="ljhemfwhz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:signal" /></template>
