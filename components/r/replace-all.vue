<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcr8bkwpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcr8bkwpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:replace-all" /></template>
