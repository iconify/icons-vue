<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w62me5ijn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w62me5ijn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:video" /></template>
