<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-57uegbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":717};
const content = `<path class="v-57uegbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:phone" /></template>
