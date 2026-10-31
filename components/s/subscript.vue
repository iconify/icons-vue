<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/e/e5qwh6ble.css';
import '../../css/v/vyut8oaub.css';
import '../../css/p/pkb4u5hql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="e5qwh6ble wm-shadow"/><path class="vyut8oaub wm-shadow"/><path class="pkb4u5hql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:subscript" /></template>
