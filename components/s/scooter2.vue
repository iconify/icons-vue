<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lql2hob3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lql2hob3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:scooter2" /></template>
