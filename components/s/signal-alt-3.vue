<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un2jr5b5x.css';
import '../../css/u/u6c0nebia.css';
import '../../css/m/m6vv16rhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="un2jr5b5x"/><path class="u6c0nebia"/><path class="m6vv16rhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:signal-alt-3" /></template>
