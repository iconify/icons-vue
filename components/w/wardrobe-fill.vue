<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jujyugb5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jujyugb5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wardrobe-fill" /></template>
