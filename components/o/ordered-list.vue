<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sef8rzbht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-6};
const content = `<path class="sef8rzbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:ordered-list" /></template>
