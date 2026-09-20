<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9tvt8oor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9tvt8oor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:smart-home4" /></template>
