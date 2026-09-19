<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/o/o_9uvrmvu.css';
import '../../css/l/lp9xhlbuq.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG9K7TFbOT"><g class="wwvp95byt"><path class="o_9uvrmvu"/><path class="lp9xhlbuq"/></g></mask></defs><path mask="url(#SVG9K7TFbOT)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:micro-sd" /></template>
