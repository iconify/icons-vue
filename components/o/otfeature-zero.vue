<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdx_z_tfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="sdx_z_tfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:otfeature-zero" /></template>
