<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofzsp5buw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofzsp5buw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:store-solid" /></template>
