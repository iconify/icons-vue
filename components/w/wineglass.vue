<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rul5p_c_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rul5p_c_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:wineglass" /></template>
