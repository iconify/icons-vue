<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glh0c68sv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="glh0c68sv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:vertical-align-top" /></template>
