<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dun1dyudb.css';
import '../../css/j/j48cmzb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dun1dyudb"/><path class="j48cmzb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:system-blocked-filled" /></template>
