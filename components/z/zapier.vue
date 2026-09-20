<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jik0o4btk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jik0o4btk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:zapier" /></template>
