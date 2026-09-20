<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4o49nlfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4o49nlfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:yii" /></template>
