<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j531q7orm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j531q7orm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:wrist-watch-round-alt" /></template>
