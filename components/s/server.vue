<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9vy97b6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9vy97b6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:server" /></template>
