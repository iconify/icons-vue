<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx6ijfbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qx6ijfbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:skaffold" /></template>
