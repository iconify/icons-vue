<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzofximaw.css';
import '../../css/k/kbosvfeuz.css';
import '../../css/x/xkwuocbvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzofximaw"/><path class="kbosvfeuz"/><path class="xkwuocbvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:paint-brush-bold" /></template>
