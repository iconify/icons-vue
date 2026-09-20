<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyidn315y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tyidn315y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:thumbtack-filled" /></template>
