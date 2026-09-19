<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvsvn_42u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":650,"height":750};
const content = `<path class="yvsvn_42u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:menu" /></template>
