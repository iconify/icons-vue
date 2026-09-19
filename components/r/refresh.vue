<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgzz_obsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pgzz_obsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:refresh" /></template>
