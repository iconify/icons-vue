<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6_1r758o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":300,"height":300};
const content = `<path class="w6_1r758o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:ngrx-state" /></template>
