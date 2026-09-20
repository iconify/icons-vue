<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgd2rnb0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgd2rnb0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:renren" /></template>
