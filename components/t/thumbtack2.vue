<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v07u4ip-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v07u4ip-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:thumbtack2" /></template>
