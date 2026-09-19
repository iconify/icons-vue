<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmbos6o5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vmbos6o5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:youtube" /></template>
