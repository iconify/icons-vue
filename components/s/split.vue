<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzjr5cb_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzjr5cb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:split" /></template>
