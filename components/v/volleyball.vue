<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvl60l-3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gvl60l-3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:volleyball" /></template>
