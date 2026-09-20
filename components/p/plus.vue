<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im830-ont.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="im830-ont"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:plus" /></template>
