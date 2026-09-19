<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bz7hrwbqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bz7hrwbqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:picasa" /></template>
