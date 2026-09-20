<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no0_jw34d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="no0_jw34d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:rotate-locked-filled" /></template>
