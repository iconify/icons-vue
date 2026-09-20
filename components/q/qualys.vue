<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvv7g0bst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvv7g0bst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:qualys" /></template>
