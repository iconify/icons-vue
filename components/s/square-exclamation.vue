<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6jc2de2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="a6jc2de2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:square-exclamation" /></template>
