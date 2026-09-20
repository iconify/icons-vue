<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iycp5mbvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iycp5mbvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:time-duration-0" /></template>
