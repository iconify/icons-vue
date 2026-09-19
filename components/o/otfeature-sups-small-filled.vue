<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1yrw_kmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="v1yrw_kmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:otfeature-sups-small-filled" /></template>
