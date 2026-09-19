<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ev061dfmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ev061dfmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:stumbleupon" /></template>
