<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx0an_mmx.css';
import '../../css/s/spq8jsdzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tx0an_mmx"/><path class="spq8jsdzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:map-add-filled" /></template>
