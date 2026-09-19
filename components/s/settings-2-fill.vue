<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6wz8cb3t.css';
import '../../css/h/h6w9bvqsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="t6wz8cb3t"/><path class="h6w9bvqsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:settings-2-fill" /></template>
