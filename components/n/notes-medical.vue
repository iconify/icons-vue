<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hat5ykuoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="hat5ykuoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:notes-medical" /></template>
