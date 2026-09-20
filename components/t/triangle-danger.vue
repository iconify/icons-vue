<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au31uekiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="au31uekiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:triangle-danger" /></template>
