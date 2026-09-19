<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfdz155uq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dfdz155uq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:tty" /></template>
