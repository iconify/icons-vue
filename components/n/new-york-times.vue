<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsh0-jb5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hsh0-jb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:new-york-times" /></template>
