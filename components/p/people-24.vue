<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/raj7bybid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="raj7bybid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:people-24" /></template>
