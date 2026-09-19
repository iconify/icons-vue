<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bazxsibde.css';
import '../../css/x/xbkw3s-py.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bazxsibde"/><path class="xbkw3s-py"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:rotate-ccw-10" /></template>
