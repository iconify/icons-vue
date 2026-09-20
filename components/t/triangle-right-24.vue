<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a05065b4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a05065b4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:triangle-right-24" /></template>
