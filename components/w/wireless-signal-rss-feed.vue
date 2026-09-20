<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/y/y46gdktui.css';
import '../../css/r/rqlsr2bvh.css';
import '../../css/f/fc2zsxbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="y46gdktui"/><path class="rqlsr2bvh"/><path class="fc2zsxbxd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:wireless-signal-rss-feed" /></template>
