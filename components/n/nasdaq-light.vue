<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlg-pycqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jlg-pycqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nasdaq-light" /></template>
