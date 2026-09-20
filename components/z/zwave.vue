<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx2589b5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xx2589b5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:zwave" /></template>
