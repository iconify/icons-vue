<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzwdv0pay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzwdv0pay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:teal" /></template>
