<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz11kf90n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zz11kf90n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:philippine-peso" /></template>
