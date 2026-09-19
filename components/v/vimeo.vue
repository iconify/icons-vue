<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/buth0fb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="buth0fb_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:vimeo" /></template>
