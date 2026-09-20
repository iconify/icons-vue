<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc1atjb6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vc1atjb6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:tools-24" /></template>
