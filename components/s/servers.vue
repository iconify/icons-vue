<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iq9qjibye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iq9qjibye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:servers" /></template>
