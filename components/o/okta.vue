<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b07s0zb2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b07s0zb2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:okta" /></template>
