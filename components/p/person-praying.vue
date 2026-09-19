<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty_o-lgmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ty_o-lgmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:person-praying" /></template>
