<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv5tshbbx.css';
import '../../css/b/b7nj-761u.css';
import '../../css/n/ndokbv5ou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yv5tshbbx"/><path class="b7nj-761u"/><path class="ndokbv5ou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:refresh-ccw-20-bold" /></template>
