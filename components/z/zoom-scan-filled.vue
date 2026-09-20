<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgi5npbgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgi5npbgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:zoom-scan-filled" /></template>
