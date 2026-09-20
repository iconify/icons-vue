<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd008e67m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dd008e67m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:social-at-circular" /></template>
