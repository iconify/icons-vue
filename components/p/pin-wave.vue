<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gd-3rgbrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gd-3rgbrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:pin-wave" /></template>
