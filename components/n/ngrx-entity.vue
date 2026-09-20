<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3rifrbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":300,"height":300};
const content = `<path class="k3rifrbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:ngrx-entity" /></template>
