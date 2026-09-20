<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdl09xb3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdl09xb3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pollinations" /></template>
