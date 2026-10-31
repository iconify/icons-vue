<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmq596bhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmq596bhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-edit-corner-round" /></template>
