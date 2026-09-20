<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-b6lmbqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-b6lmbqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:olympic-torch" /></template>
