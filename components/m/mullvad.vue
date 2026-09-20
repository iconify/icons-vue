<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdq8m0blv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdq8m0blv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:mullvad" /></template>
