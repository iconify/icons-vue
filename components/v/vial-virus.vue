<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu03ixb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="bu03ixb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:vial-virus" /></template>
