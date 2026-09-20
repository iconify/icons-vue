<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tccwmtghs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tccwmtghs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:video-library-filled" /></template>
