<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/b/b2j3gwbef.css';
import '../../css/h/hekjs4bre.css';
import '../../css/y/yooq7cc4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="b2j3gwbef wm-shadow"/><path class="hekjs4bre wm-shadow"/><path class="yooq7cc4a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:table-of-contents" /></template>
