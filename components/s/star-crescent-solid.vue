<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chq-6r-9v.css';
import '../../css/b/btvzwg_0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chq-6r-9v"/><path class="btvzwg_0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:star-crescent-solid" /></template>
