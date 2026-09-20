<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/puqu-ccha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="puqu-ccha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:plus-24" /></template>
