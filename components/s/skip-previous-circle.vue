<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-oj-cj7f.css';
import '../../css/b/bwibdw4bb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-oj-cj7f"/><path class="bwibdw4bb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:skip-previous-circle" /></template>
