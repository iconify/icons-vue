<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvitn_tfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvitn_tfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:udotsdotnews" /></template>
