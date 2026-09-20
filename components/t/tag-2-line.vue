<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba874dbxc.css';
import '../../css/r/r-_tixcty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ba874dbxc"/><path class="r-_tixcty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tag-2-line" /></template>
