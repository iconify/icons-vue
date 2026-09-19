<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw4fvnrev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uw4fvnrev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:vend" /></template>
