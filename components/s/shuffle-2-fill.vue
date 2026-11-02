<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odxm166en.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odxm166en"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:shuffle-2-fill" /></template>
