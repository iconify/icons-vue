<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1y3p2mzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s1y3p2mzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:share" /></template>
