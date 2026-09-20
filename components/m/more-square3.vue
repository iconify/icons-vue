<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmxebib_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmxebib_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:more-square3" /></template>
