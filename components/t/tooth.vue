<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utegbx69l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utegbx69l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tooth" /></template>
