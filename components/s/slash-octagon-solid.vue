<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py0v7ob5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="py0v7ob5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:slash-octagon-solid" /></template>
