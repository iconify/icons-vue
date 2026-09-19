<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knw-0m56b.css';
import '../../css/x/xr22nd2nm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knw-0m56b"/><path class="xr22nd2nm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:science-filled" /></template>
