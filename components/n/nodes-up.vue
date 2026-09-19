<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u01px0b2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="u01px0b2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:nodes-up" /></template>
