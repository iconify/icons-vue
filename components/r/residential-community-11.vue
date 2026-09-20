<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4s140a6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="l4s140a6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:residential-community-11" /></template>
