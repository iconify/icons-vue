<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxxewcb7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="oxxewcb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:mammography" /></template>
