<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gunf1bbcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="gunf1bbcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:vkontakte-rect" /></template>
