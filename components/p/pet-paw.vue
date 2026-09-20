<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uatd2gfja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uatd2gfja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:pet-paw" /></template>
