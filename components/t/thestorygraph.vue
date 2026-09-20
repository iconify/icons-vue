<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixd3b-p8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixd3b-p8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:thestorygraph" /></template>
