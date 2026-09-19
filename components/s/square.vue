<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5jhaob4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5jhaob4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:square" /></template>
