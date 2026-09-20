<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-wmb0bhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-wmb0bhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:qiita" /></template>
