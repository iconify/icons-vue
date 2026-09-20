<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvtlfgbug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvtlfgbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:navigation-off" /></template>
