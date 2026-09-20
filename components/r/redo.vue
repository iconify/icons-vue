<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omllgdbsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-1,"top":-2};
const content = `<path class="omllgdbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:redo" /></template>
