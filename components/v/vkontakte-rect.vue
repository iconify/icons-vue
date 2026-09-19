<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kh55srbkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="kh55srbkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="brandico:vkontakte-rect" /></template>
