<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5u5fxb_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5u5fxb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:memory" /></template>
