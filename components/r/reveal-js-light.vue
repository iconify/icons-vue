<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk87_smea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mk87_smea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:reveal-js-light" /></template>
