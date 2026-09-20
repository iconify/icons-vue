<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr9n_rb2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xr9n_rb2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:menlo-lucy-jan-nano" /></template>
