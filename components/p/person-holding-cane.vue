<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct9hup_mh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ct9hup_mh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-holding-cane" /></template>
