<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usxnfizjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usxnfizjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:panel-top" /></template>
