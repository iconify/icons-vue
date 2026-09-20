<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxk2dtb4g.css';
import '../../css/m/m9vpipbzf.css';
import '../../css/g/gnxfpjl9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxk2dtb4g"/><path class="m9vpipbzf"/><path class="gnxfpjl9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:speaker-stand" /></template>
