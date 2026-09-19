<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd0hveb6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qd0hveb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:windows" /></template>
