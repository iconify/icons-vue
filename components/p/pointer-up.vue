<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwc74bb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwc74bb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pointer-up" /></template>
