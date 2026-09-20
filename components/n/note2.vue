<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-bhugbfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-bhugbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:note2" /></template>
