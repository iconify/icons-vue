<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4-my4brf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4-my4brf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:microfocus" /></template>
