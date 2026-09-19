<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjrnk-4ya.css';
import '../../css/j/j02epxblr.css';
import '../../css/o/o3j-a-5dv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjrnk-4ya"/><path class="j02epxblr"/><path class="o3j-a-5dv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:webhook-filled" /></template>
