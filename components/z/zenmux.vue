<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b69reo12v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b69reo12v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:zenmux" /></template>
