<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yot74wbfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yot74wbfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sunset-fill" /></template>
