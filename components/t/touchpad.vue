<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckoedbb2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ckoedbb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:touchpad" /></template>
