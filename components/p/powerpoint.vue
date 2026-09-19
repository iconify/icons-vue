<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/g/g47cb4b4t.css';
import '../../css/u/uqqqq-ifh.css';
import '../../css/b/b-tt1pblw.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGA76BUfcL"><g class="s9cl3zbei"><rect class="g47cb4b4t"/><path class="uqqqq-ifh"/><path class="b-tt1pblw"/></g></mask></defs><path mask="url(#SVGA76BUfcL)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:powerpoint" /></template>
