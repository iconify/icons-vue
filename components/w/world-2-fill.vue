<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvxj0b0tu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvxj0b0tu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:world-2-fill" /></template>
