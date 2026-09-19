<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok--3pvjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ok--3pvjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:route" /></template>
