<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0dcn3bcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0dcn3bcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:strike-through" /></template>
