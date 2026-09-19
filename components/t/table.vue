<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzzcvzb9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzzcvzb9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:table" /></template>
