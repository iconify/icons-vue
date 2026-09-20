<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zoj4zbc2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zoj4zbc2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:nutanix" /></template>
