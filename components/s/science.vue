<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3g5p9b8f.css';
import '../../css/x/xr22nd2nm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3g5p9b8f"/><path class="xr22nd2nm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:science" /></template>
