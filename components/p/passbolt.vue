<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfrd9db5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfrd9db5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:passbolt" /></template>
