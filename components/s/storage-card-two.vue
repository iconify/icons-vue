<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/w/wiah3db5h.css';
import '../../css/q/q4b4fq76m.css';
import '../../css/j/j2bnel5xz.css';
import '../../css/s/srjtb2b8l.css';
import '../../css/t/t-hikcb2l.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGFbYCpcUB"><g class="s9cl3zbei"><rect class="wiah3db5h"/><path class="q4b4fq76m"/><path class="j2bnel5xz"/><path class="srjtb2b8l"/><path class="t-hikcb2l"/></g></mask></defs><path mask="url(#SVGFbYCpcUB)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:storage-card-two" /></template>
