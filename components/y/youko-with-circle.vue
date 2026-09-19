<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3sktvbkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b3sktvbkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:youko-with-circle" /></template>
