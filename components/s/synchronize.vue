<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvxvdibsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zvxvdibsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:synchronize" /></template>
