<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajx912bas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajx912bas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:wifi-low" /></template>
