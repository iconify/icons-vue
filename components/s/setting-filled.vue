<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktz_dipcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktz_dipcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:setting-filled" /></template>
