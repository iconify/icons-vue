<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c49zb3b7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c49zb3b7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:text-wrap" /></template>
