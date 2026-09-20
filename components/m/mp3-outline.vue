<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/przcfuwhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="przcfuwhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:mp3-outline" /></template>
