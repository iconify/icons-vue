<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/et57vxgoa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="et57vxgoa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:plus-a" /></template>
