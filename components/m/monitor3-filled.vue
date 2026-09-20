<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6fo3wqws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6fo3wqws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:monitor3-filled" /></template>
