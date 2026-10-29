<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpz5whbxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpz5whbxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:thumbs-down-solid" /></template>
