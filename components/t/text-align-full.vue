<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqy36v4km.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqy36v4km"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:text-align-full" /></template>
