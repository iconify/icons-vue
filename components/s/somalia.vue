<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xiewx4bml.css';
import '../../css/t/ta73ae7hy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="xiewx4bml"/><path class="ta73ae7hy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:somalia" /></template>
