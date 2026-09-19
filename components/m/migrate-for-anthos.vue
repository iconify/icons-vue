<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcn2q1bcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcn2q1bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:migrate-for-anthos" /></template>
