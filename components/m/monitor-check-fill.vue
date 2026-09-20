<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zivg1ubor.css';
import '../../css/a/az-qmkb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zivg1ubor"/><path clip-rule="evenodd" class="az-qmkb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:monitor-check-fill" /></template>
