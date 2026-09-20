<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkem5w7zw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkem5w7zw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:sparkasse" /></template>
