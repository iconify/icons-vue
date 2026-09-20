<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/px7f85dfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="px7f85dfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:picxy" /></template>
