<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or4e17b8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="or4e17b8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:new-folder-fill" /></template>
