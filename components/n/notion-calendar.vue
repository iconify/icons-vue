<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxq-hubfm.css';
import '../../css/z/zylz4v1cy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dxq-hubfm"/><path class="zylz4v1cy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:notion-calendar" /></template>
