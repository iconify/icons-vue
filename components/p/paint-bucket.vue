<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltdby2oqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ltdby2oqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:paint-bucket" /></template>
