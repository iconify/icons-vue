<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2bkmibuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":300,"height":300};
const content = `<path class="m2bkmibuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:ngrx-effects" /></template>
