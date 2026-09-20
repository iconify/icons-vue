<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4sf2hbdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="w4sf2hbdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:male" /></template>
