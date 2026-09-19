<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn7bfp_tc.css';
import '../../css/t/tfentzbbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hn7bfp_tc"/><circle class="tfentzbbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:palette" /></template>
