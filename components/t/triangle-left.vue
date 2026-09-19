<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmi1g064l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xmi1g064l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:triangle-left" /></template>
