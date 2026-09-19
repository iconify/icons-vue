<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to3-oybdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="to3-oybdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shadows-filled" /></template>
