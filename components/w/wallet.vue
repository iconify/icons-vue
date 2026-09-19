<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajd5gdbqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ajd5gdbqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:wallet" /></template>
