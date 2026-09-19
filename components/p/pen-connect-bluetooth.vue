<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsih-mv_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hsih-mv_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:pen-connect-bluetooth" /></template>
