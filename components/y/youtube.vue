<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm0unvb9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xm0unvb9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:youtube" /></template>
