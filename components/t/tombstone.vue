<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/al-4-0btz.css';
import '../../css/t/twbohlb9d.css';
import '../../css/l/l9h-wybvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="al-4-0btz wm-k"/><path class="twbohlb9d wm-a"/><path class="l9h-wybvf wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:tombstone" /></template>
