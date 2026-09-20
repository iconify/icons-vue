<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zivg1ubor.css';
import '../../css/t/tis47ojmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zivg1ubor"/><path clip-rule="evenodd" class="tis47ojmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:monitor-pause-fill" /></template>
