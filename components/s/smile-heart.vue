<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anficybsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anficybsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:smile-heart" /></template>
