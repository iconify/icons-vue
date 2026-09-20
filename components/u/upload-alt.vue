<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh93e5uni.css';
import '../../css/c/c22lcubke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bh93e5uni"/><path class="c22lcubke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:upload-alt" /></template>
