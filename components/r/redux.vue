<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odbl_absp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="odbl_absp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:redux" /></template>
