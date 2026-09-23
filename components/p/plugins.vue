<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtz5swbmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="dtz5swbmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:plugins" /></template>
