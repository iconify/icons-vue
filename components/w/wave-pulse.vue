<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gajor1bst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gajor1bst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:wave-pulse" /></template>
