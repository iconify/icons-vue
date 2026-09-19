<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k47n0ww8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k47n0ww8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:play" /></template>
