<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0hskbc8u.css';
import '../../css/a/af2lrdbuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y0hskbc8u"/><path class="af2lrdbuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sofa-3-bold-duotone" /></template>
