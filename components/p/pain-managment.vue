<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfpuc6bso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="nfpuc6bso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:pain-managment" /></template>
