<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv2z8xbnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qv2z8xbnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:triangle-left-fill" /></template>
