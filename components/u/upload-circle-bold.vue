<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qc57vg_un.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qc57vg_un"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:upload-circle-bold" /></template>
