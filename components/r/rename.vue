<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt-gltsgq.css';
import '../../css/e/eb4ipfkkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nt-gltsgq"/><path class="eb4ipfkkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:rename" /></template>
