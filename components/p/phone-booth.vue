<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ougc4bcup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ougc4bcup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:phone-booth" /></template>
