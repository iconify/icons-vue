<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_p-bomet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="p_p-bomet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:roadwork" /></template>
