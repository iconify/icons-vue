<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwhtb-9yk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwhtb-9yk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:redox" /></template>
