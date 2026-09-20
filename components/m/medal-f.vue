<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugymjwbui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4,"top":-1};
const content = `<path class="ugymjwbui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:medal-f" /></template>
