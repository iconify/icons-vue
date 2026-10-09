<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrkewflek.css';
import '../../css/h/hwjgqrbah.css';
import '../../css/y/y9mg2tbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jrkewflek"/><path class="hwjgqrbah"/><path class="y9mg2tbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pets-allowed-48-bold" /></template>
