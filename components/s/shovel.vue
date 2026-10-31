<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/a/a5d0hccew.css';
import '../../css/w/w09p6yc8f.css';
import '../../css/e/ere1wq24f.css';
import '../../css/r/r7f535bef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="a5d0hccew wm-shadow"/><path class="w09p6yc8f wm-shadow"/><path class="ere1wq24f"/><path class="r7f535bef"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:shovel" /></template>
