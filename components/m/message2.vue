<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n01jmhb7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n01jmhb7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:message2" /></template>
