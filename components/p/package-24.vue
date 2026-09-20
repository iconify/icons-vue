<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gx5vngb9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gx5vngb9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:package-24" /></template>
