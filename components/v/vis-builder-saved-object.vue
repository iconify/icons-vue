<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8s6xvu0y.css';
import '../../css/v/v-nzisfqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w8s6xvu0y"/><path class="v-nzisfqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:vis-builder-saved-object" /></template>
