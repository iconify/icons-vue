<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iee2udl7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="iee2udl7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:screen" /></template>
