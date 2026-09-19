<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zctrsbc9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zctrsbc9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:shield-check" /></template>
