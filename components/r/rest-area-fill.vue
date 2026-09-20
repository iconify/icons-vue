<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvz50ne4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvz50ne4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rest-area-fill" /></template>
