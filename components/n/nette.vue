<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aob9_pbxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aob9_pbxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nette" /></template>
