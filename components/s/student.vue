<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_11zobnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="p_11zobnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:student" /></template>
