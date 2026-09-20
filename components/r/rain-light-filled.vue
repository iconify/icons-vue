<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/boc6a8b6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="boc6a8b6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:rain-light-filled" /></template>
