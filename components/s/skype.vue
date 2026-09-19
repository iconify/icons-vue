<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wigw2ob_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wigw2ob_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:skype" /></template>
