<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/np-3k1nzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="np-3k1nzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:new" /></template>
