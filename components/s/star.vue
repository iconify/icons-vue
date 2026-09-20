<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp9a9d94n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xp9a9d94n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:star" /></template>
