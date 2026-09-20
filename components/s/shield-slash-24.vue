<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j54ttfgtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j54ttfgtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:shield-slash-24" /></template>
