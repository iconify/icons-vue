<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkibz-bio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="gkibz-bio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:snooker" /></template>
