<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cime-tbhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="cime-tbhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:toilet-sign-man-solid" /></template>
