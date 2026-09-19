<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pt_yvmwhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pt_yvmwhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:renren" /></template>
