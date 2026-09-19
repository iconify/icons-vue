<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv8tf136m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nv8tf136m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:table-cells" /></template>
