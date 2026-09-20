<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl7hxid5w.css';
import '../../css/r/rs4bqbchn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yl7hxid5w"/><path class="rs4bqbchn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:urus" /></template>
