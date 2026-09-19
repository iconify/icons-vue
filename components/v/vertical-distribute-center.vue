<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn8j55bys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hn8j55bys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:vertical-distribute-center" /></template>
