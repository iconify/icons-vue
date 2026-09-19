<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r5ke29wou.css';
import '../../css/r/rftmvky-i.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGBKRtqbaD"><g class="ft5dv1b6b"><rect class="r5ke29wou"/><path class="rftmvky-i"/></g></mask></defs><path mask="url(#SVGBKRtqbaD)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:reduce-two" /></template>
